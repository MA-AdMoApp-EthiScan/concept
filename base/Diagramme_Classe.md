classDiagram
    class EthiscanUser {
        String uid
        List~FavoriteProduct~ favoriteProducts
        List~String~ metadataTypeIds
    }

    class FavoriteProduct {
        String productId
        DateTime addedAt
    }

    class Product {
        String id
        String name
        String imageUrl
        String description
        List~String~ certificationIds
        List~String~ productMetadataIds
    }

    class Certification {
        String id
        String name
        String description
        String imageUrl
    }

    class Supplier {
        String name
        List~SoldProduct~ products
    }

    class SoldProduct {
        String productId
        double price
    }

    class MetadataType {
        String id
        String name
        Map~String, dynamic~ schema
    }

    class ProductMetadata {
        String id
        String metadataTypeId
        Map~String, dynamic~ data
    }

    EthiscanUser --> User : 1
    EthiscanUser --> FavoriteProduct : 0..* contains
    EthiscanUser --> MetadataType : 0..* subscribes to

    FavoriteProduct --> Product : 1 refers to

    Product --> Certification : 0..* refers to
    Product --> ProductMetadata : 0..* has many

    Supplier --> SoldProduct : 0..* sells

    SoldProduct --> Product : 1 refers to

    ProductMetadata --> MetadataType : 1 has

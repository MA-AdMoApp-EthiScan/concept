classDiagram
    class EthiscanUser {
        User user
        List~FavoriteProduct~ favoriteProducts
        UserPreferences userPreferences
    }

    class FavoriteProduct {
        Product product
        DateTime addedAt
    }

    class Product {
        String id
        String name
        String imageUrl
        String description
        Certification certification
        List~ProductMetadata~ productMetadatas
    }

    class Certification {
        String name
        String description
        String imageUrl
    }

    class Supplier {
        String name
        List~SoldProduct~ products
    }

    class SoldProduct {
        Product product
        double price
    }

    class MetadataType {
        String name
        Map~String, dynamic~ schema
    }

    class ProductMetadata {
        MetadataType type
        Map~String, dynamic~ data
    }

    class UserPreferences {
        List~MetadataType~ metadataSubscriptions
    }

    EthiscanUser --> User : 1
    EthiscanUser --> FavoriteProduct : 0..* contains
    EthiscanUser --> UserPreferences : 1 has

    FavoriteProduct --> Product : 1 contains

    Product --> Certification : 0..1 has
    Product --> ProductMetadata : 0..* has many

    Supplier --> SoldProduct : 0..* sells

    SoldProduct --> Product : 1 refers to

    ProductMetadata --> MetadataType : 1 has

    UserPreferences --> MetadataType : 0..* subscribes to

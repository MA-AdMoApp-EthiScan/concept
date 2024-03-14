# User Stories

## Characters

### Alice

genre: femme
age: 28 ans
intérêt: consommation responsable, écolo
richesse: classe moyenne
relations: en concubinage avec Bob

### Bob

genre: homme
age: 27 ans
intérêt: économie, consommation responsable
richesse: classe moyenne
allergies: gluten, lactose
relations: en concubinage avec Alice

### Croquette

genre: chien
age: 3 ans
intérêt: manger, exigeant
allergies: aucune
relations: chien de Alice et Bob

## User Stories

### 1. En tant qu'utilisateur, je veux pouvoir scanner un produit pour obtenir des informations détaillées sur celui-ci

- **Priorité** : Must Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'utilisateur peut scanner un produit en utilisant la caméra de son téléphone.
  - L'application affiche les informations détaillées du produit scanné (Metadata)
- **Histoire**: Alice et Bob sont dans un supermarché et veulent acheter des produits alimentaires. Ils veulent pouvoir scanner les produits pour obtenir des informations détaillées sur ceux-ci. Par exemple, ils veulent savoir si le produit est bio, local, s'il contient des allergènes, etc.

### 2. En tant qu'utilisateur, je veux pouvoir ajouter un produit à une liste de favoris pour un accès rapide

- **Priorité** : Nice to Have
- **Difficulté** : Facile
- **Critères d'acceptation** :
  - L'utilisateur peut ajouter un produit à une liste de favoris.
  - L'utilisateur peut consulter sa liste de favoris.
- **Histoire**: Alice et Bob veulent pouvoir ajouter des produits à une liste de favoris pour un accès rapide. Par exemple, ils veulent pouvoir ajouter des produits qu'ils achètent régulièrement à leur liste de favoris.

### 3. En tant qu'utilisateur, je veux pouvoir configurer mes préférences d'achat pour recevoir des informations personnalisées

- **Priorité** : Must Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'utilisateur peut configurer ses préférences d'achat (metadata) (local, bio, qualité, prix, impact carbone, durabilité de l'emballage, livrable par la poste).
  - L'application affiche des informations personnalisées en fonction des préférences de l'utilisateur.
- **Histoire**: Alice a scanné un produit et est abonnée au metadata Labels. Elle cherche à trouver le label bio sur le produit scanné.

### 4. En tant qu'utilisateur, je veux pouvoir consulter les labels et certifications des produits scannés (Certification = Metadata)

- **Priorité** : Nice to Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'application affiche les labels et certifications des produits scannés.
- **Histoire**: Alice et Bob veulent pouvoir consulter les labels et certifications des produits scannés. Par exemple, ils veulent savoir si le produit est bio, s'il a des labels environnementaux, etc.

### 5. En tant qu'utilisateur, je veux pouvoir consulter l'évolution du prix des produits scannés (metadata)

- **Priorité** : Nice to Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'application affiche l'évolution du prix des produits scannés chez différents fournisseurs.
- **Histoire**: Alice et Bob veulent pouvoir consulter l'évolution du prix des produits scannés. Par exemple, ils veulent savoir si le prix du produit a augmenté ou diminué récemment.

### 6. En tant qu'utilisateur, je veux pouvoir consulter l'impact carbone des produits scannés (metadata)

- **Priorité** : Nice to Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'application affiche l'impact carbone des produits scannés.
- **Histoire**: Alice et Bob veulent pouvoir consulter l'impact carbone des produits scannés. Par exemple, ils veulent savoir si le produit a un impact carbone élevé ou faible.

### 8. En tant qu'utilisateur, j'aimerais pouvoir trouver des produits similaires à celui que j'ai scanné

- **Priorité** : Nice to Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'application affiche des produits similaires à celui scanné.
- **Histoire**: Bob trouve une boîte de conserve de haricots verts à la coop, elle aimerait savoir si elle peut trouver un produit similaire moins cher ailleurs.

### 8. En tant qu'utilisateur, j'aimerais pouvoir filtrer les produits similaire par importance en fonction de mes préférences (metadata)

- **Priorité** : Nice to Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'application affiche des produits similaires à celui scanné.
  - L'utilisateur peut filtrer les produits similaires par importance en fonction de ses préférences.
- **Histoire**: Bob trouve une boîte de conserve de haricots verts à la coop, elle aimerait savoir si elle peut trouver un produit similaire moins cher ailleurs.

### 9. En tant qu'utilisateur, je veux pouvoir ajouter une importance sur les metadata que je suis abonné, pour que l'application préfère les produits qui respectent ces metadata au mieux

- **Priorité** : Nice to Have
- **Difficulté** : Moyen
- **Critères d'acceptation** :
  - L'utilisateur peut ajouter une importance sur les metadata qu'il suit.
  - L'application préfère les produits qui respectent ces metadata au mieux.
- **Histoire**: Alice réalise un gâteau d'aniversaire pour Bob, elle souhaiterait trouver une farine sans gluten pour que Bob puisse en manger. Alors elle souhaiterait similaire soient sans gluten avant d'être moins cher.

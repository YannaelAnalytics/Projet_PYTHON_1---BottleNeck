# 📘 Dictionnaire de données

Le but du projet est de fusionner les tables "erp", "web" et "caracteristiques_vins" en une seule table, "df_boutique_web". Je ne fournis ici que le dictionnaire des données de la table finale :

## Table `df_boutique_web`

| Champ                     | Type    | Contrainte   | Description                                                                                                |
|---------------------------|---------|--------------|------------------------------------------------------------------------------------------------------------|
| `product_id`              | INTEGER | Clé Primaire | Identifiant unique pour chaque produit                                                                     |
| `price`                   | FLOAT   |              | Prix de l'article                                                                                          |
| `stock_quantity`          | INTEGER |              | Quantité du produit dans le stock de la boutique                                                           |
| `stock_status`            | INTEGER |              | Statut des stocks pour le `product_id`                                                                     |
| `id_web`                  | INTEGER |              | Identifiant unique pour chaque produit sur le site web                                                     |
| `total_sales`             | FLOAT   |              | Nombre de ventes                                                                                           |
| `post_title`              | INTEGER |              | Nom complet du produit                                                                                     |
| `post_excerpt`            | INTEGER |              | Description du produit                                                                                     |
| `post_name`               | INTEGER |              | Nom du produit qui sert de clé pour une jointure                                                           |
| `guid`                    | INTEGER |              | Lien de la page produit de la boutique web                                                                 |
| `post_type`               | INTEGER |              | Type de publication web                                                                                    |
| `poids`                   | INTEGER |              | Masse du produit                                                                                           |
| `Région`                  | INTEGER |              | Région de fabrication du produit                                                                           |
| `Domaine`                 | INTEGER |              | Nom du domaine de fabrication                                                                              |
| `Appellation`             | INTEGER |              | Nom de l'appellation du produit                                                                            |
| `Couleur`                 | INTEGER |              | Couleur du produit                                                                                         |
| `Cepage`                  | INTEGER |              | Cepage d'origine du produit                                                                                | 
| `Millésime`               | FLOAT   |              | Année de fabrication du produit                                                                            |
| `Garde`                   | INTEGER |              | Durée de garde conseillé                                                                                   |
| `Contenance`              | INTEGER |              | Contenance du produit                                                                                      |
| `Degré d'alcool`          | INTEGER |              | Degré d'alcool du produit                                                                                  |
| `Température dégustation` | INTEGER |              | Température dégustation conseillée du produit                                                              | 
| `Alliance mets`           | INTEGER |              | Association conseillée avec le produit                                                                     |

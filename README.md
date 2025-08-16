# 📊 Rapprochement ERP & Boutique en ligne

Projet réalisé dans le but d'améliorer la visibilité des ventes en ligne et la fiabilité des données produits.

---

## 🚀 Objectif du projet

Mettre en place un processus de rapprochement de données entre l’ERP et la boutique en ligne afin de :

- Fusionner les exports produits (ERP + Web) grâce au mapping product_id ↔ SKU.

- Calculer le chiffre d’affaires par produit et le CA total en ligne.

- Réaliser une analyse exploratoire des prix pour détecter d’éventuelles valeurs aberrantes.

- Produire un dataset consolidé exportable en Excel pour partage.

---

## 🛠️ Outils & Librairies

- Jupyter Notebook : exploration et documentation du travail

- Python : traitement et nettoyage de données

- Pandas : fusion, manipulation et analyse des datasets

- Plotly : visualisations interactives des anomalies de prix

---

## 📂 Données utilisées

- `erp.xlsx` → références produits, prix, stock

- `web.xlsx` → informations produits et ventes en ligne

- mapping.xlsx → correspondance product_id ↔ SKU

- `caracteristiques_vins.csv` → caractéristiques complémentaires (optionnel)

## 📈 Livrables

- 📑 Dataset final fusionné (dataset_fusionné.xlsx)

- 📊 Graphiques interactifs (analyse des prix)

- 🎯 Présentation synthétique des résultats et du workflow

---

## 💡 Résultats obtenus

- Consolidation des données ERP + Web en une base unique

- Calcul automatique du CA total et par produit

- Identification de valeurs aberrantes dans les prix, illustrées par graphiques Plotly

# 📘 Dictionnaire de données des 5 tables

## Table `df_web`

| Champ                     | Type   | Contrainte   | Description                                                                                                |
|---------------------------|--------|--------------|------------------------------------------------------------------------------------------------------------|
| `Project_ID`              | STRING |              | Identifiant unique pour chaque projet. Il y a plusieurs lignes pour chaque ID projet car plusieurs phases  |
| `Phase`                   | STRING |              | Phase du projet                                                                                            |
| `Start Date`              | DATE   |              | Date de départ d'un projet                                                                                 |
| `Planned_Duration`        | FLOAT  |              | Nombre de jours prévus par phase. Estimation renseignée par l'équipe en charge                             |
| `Planned_Cost`            | FLOAT  |              | Coûts prévus (en $) pour achever la phase de projet associée. Estimation renseignée par l'équipe en charge |

| Champ                     | Type   | Contrainte   | Description                                

## Table de Dimensions 1 : `df_erp`

| Champ                     | Type   | Contrainte   | Description                                                                                                |
|---------------------------|--------|--------------|------------------------------------------------------------------------------------------------------------|
| `Project_ID`              | STRING | Clé Primaire | Identifiant unique pour chaque projet.                                                                     |
| `Project Type`            | STRING |              | Type de projet : IT ou Marketing                                                                           |

## Table de Faits 2 : `df_liaison`

| Champ                     | Type   | Contrainte   | Description                                                                                               |
|---------------------------|--------|--------------|-----------------------------------------------------------------------------------------------------------|
| `Project_ID`              | STRING |              | Identifiant unique pour chaque projet. Il y a plusieurs lignes pour chaque ID projet car plusieurs phases |
| `Phase`                   | STRING |              | Phase du projet                                                                                           |
| `Actual_Cost              | FLOAT  |              | Coût réel (en $) constaté de la phase du projet. Donnée resneignéee à la fin de la phase                  |

## Table de Faits 3 : `df_caracteristiques`

| Champ                     | Type   | Contrainte   | Description                                                                                               |
|---------------------------|--------|--------------|-----------------------------------------------------------------------------------------------------------|
| `Project_ID`              | STRING |              | Identifiant unique pour chaque projet. Il y a plusieurs lignes pour chaque ID projet car plusieurs phases |
| `Phase`                   | STRING |              | Phase du projet                                                                                           |
| `Actual_Duration`         | FLOAT  |              | Nombre de jours nécessaires pour achever la phase du projet. Constaté à la fin de chaque phase            |

## Table de Faits 4 : `Deliverables_sta



# 📊 Power BI Dashboard - Analyse des Ventes Multi-Boutiques

Ce projet Power BI est basé sur une **analyse complète des ventes**, incluant des données sur les boutiques, les produits et les transactions. Il s'agit d'un tableau de bord interactif qui permet de visualiser les performances commerciales par période, catégorie, localisation, etc.

## 📁 Structure du dashboard

📌 Onglet 1 – Ventes
Cet onglet est dédié à l’analyse détaillée du chiffre d’affaires et du volume de ventes sur une période donnée. Il met en avant les indicateurs clés de performance (KPI) comme le CA total, le CA de l’année précédente, et l’évolution mensuelle des ventes. Des graphiques circulaires et barres permettent de comparer le chiffre d’affaires selon la catégorie de produit, la marque ou encore la classe (Regular, Deluxe, Economy). Une visualisation combinée (graphique double axe) montre la corrélation entre le CA et le nombre de ventes au fil du temps. Un tableau mensuel complète l’analyse en détaillant les écarts entre les années, avec des indicateurs de tendance (flèches). Enfin, une table détaille les ventes par produit pour une analyse fine.

📌 Onglet 2 – Produits
L’objectif de cet onglet est de comprendre la répartition et la performance des produits commercialisés. On y retrouve le nombre total de produits, ainsi qu’une visualisation des produits par catégorie principale. Un graphique en courbes compare les retours clients avec les ventes, pour identifier les produits problématiques. Une visualisation de type hiérarchie (arborescence) présente la structure produits par catégorie et sous-catégorie, offrant une vue synthétique de l’offre. Une carte de ventes par produit permet d’identifier les meilleurs contributeurs, tandis qu’un tableau final liste les détails de chaque produit, ses caractéristiques et son positionnement.

📌 Onglet 3 – Boutiques
Ce dernier onglet est centré sur la dimension géographique et structurelle du réseau de distribution. Il affiche le nombre total de boutiques actives, leur répartition par type (Store, Online, Reseller) et leur statut (actif/inactif). Une carte géographique permet de visualiser leur localisation mondiale, filtrable par continent ou pays. Des indicateurs supplémentaires montrent le nombre d’employés par boutique et la surface de vente. Un tableau synthétise les caractéristiques principales de chaque boutique, et une visualisation par barres verticales affiche le nombre de ventes par point de vente, pour identifier les boutiques les plus performantes.

## 🧩 Données
Les données sont simulées et disponibles dans un fichier Excel fourni (fichier d’exemple `Dataset_Sales.xlsx`).

Colonnes clés :
- `Date`, `IdVente`, `Produit`, `Marque`
- `Pays`, `Boutique`, `Type`, `Statut`
- `Quantité`, `Montant vente`, `Montant vente après`

## 🛠 Outils utilisés
- Microsoft Power BI Desktop
- Excel pour la préparation des données

## 🎯 Objectifs pédagogiques
- Créer un dashboard de ventes interactif
- Utiliser des segments avancés
- Comparer des KPI par période
- Visualiser la performance géographique
- Maîtriser les graphiques combinés et les indicateurs de tendance.
- Structurer l’analyse en onglets thématiques pour améliorer la lisibilité et la navigation dans le rapport.
- 

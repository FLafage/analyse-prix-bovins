# 📈 Analyse et Prédiction des Prix de la Carcasse Bovine (1996-2026)

Ce projet propose une étude complète des cotations hebdomadaires de gros bovins en France, basée sur les données officielles de **FranceAgriMer**.

## 🔗 https://visionet.franceagrimer.fr/pages/SeriesChronologiques.aspx?menuurl=SeriesChronologiques/productions%20animales/viandes/gros%20bovins%20entr%C3%A9e%20abattoir

## 🎯 Objectifs du Projet
* **Nettoyage de données** : Conversion historique Francs/Euros et gestion des séries temporelles sur 30 ans.
* **Analyse Statistique** : Mise en évidence d'une rupture de marché historique à partir de 2021.
* **Modélisation ARIMA** : Prédiction des cours pour le premier trimestre 2026.

## 📊 Résultats Clés
* **Cohésion du marché** : Une corrélation de Pearson proche de **1.00** entre toutes les catégories EUROP.
* **Performance du modèle** : Un score **R² de 0.9997** validant la robustesse de l'analyse.
* **Projection 2026** : Une tendance identifiée vers les **8 €/kg** pour la catégorie R3.

## 🛠️ Outils utilisés
* **R / Quarto**
* **Tidyverse** (Dplyr, Tidyr)
* **Highcharter** (Visualisations interactives)
* **Forecast** (Modèles ARIMA)

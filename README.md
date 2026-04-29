# Projet_R
Projet d'analyse et de modélisation réalisé en Master Data Analyst à l'IAE Paris-Est
# 🕵️‍♂️ Analyse des Comportements d'Achat et Détection de Fraudes (Cosmétique de Luxe)

## 📌 Contexte du projet
[cite_start]Ce projet d'étude, réalisé dans le cadre de mon Master 1 Data Analyst à l'IAE Paris-Est, explore les dynamiques de vente et les incidents frauduleux dans le secteur des cosmétiques haut de gamme[cite: 137, 160]. [cite_start]L'objectif est d'identifier les similarités et dissimilarités de comportement selon la localisation géographique et le type de point de vente[cite: 161, 167].

## 📊 Jeu de Données
* [cite_start]**Source :** Données extraites de Kaggle portant sur la période de février à août 2025[cite: 167, 169].
* [cite_start]**Volume :** 2 133 observations internationales[cite: 168].
* [cite_start]**Variables clés :** Montant d'achat, affluence quotidienne (Footfall), type de boutique (Popup, Flagship, etc.), et indicateur de fraude (Fraud_Flag)[cite: 180, 183, 186, 187].

## 🛠️ Méthodologie et Outils
* [cite_start]**Langage :** R (Statistiques descriptives et inférentielles)[cite: 140, 163].
* [cite_start]**Traitement des données :** Nettoyage et création de nouvelles variables (`store_ville` et `store_type`) pour affiner l'analyse spatiale[cite: 188].
* **Analyses effectuées :**
  1. [cite_start]**Statistiques descriptives :** Étude du panier moyen (175$) et de l'affluence moyenne (272 visiteurs/jour)[cite: 255, 254].
  2. [cite_start]**Data Visualisation :** Comparaison du taux de fraude par ville et analyse du montant d'achat via des boîtes à moustaches[cite: 241, 339].
  3. [cite_start]**Tests Statistiques :** Tests de normalité, Test du $Khi^{2}$, Corrélation de Pearson et Test de Wilcoxon[cite: 163, 423, 427, 440].

## 📈 Résultats et Conclusions Clés
* [cite_start]**Géographie de la fraude :** Las Vegas présente le taux de fraude le plus élevé (8%), tandis que Paris et Genève enregistrent 0% de fraude sur l'échantillon[cite: 266].
* **Profils de paiement :** Hétérogénéité marquée selon les villes. [cite_start]La carte cadeau est privilégiée dans les zones touristiques (Paris, Tokyo), tandis que le paiement mobile domine à Hong Kong et New York[cite: 415, 416, 418].
* **Validation Statistique :**
  * [cite_start]Le test du $Khi^{2}$ ($p-value = 0.18$) révèle qu'il n'y a **pas de dépendance significative** entre le type de boutique et la fraude[cite: 425, 426].
  * [cite_start]Le test de Wilcoxon ($p-value = 0.33$) démontre qu'il n'y a **pas de différence significative** de montant d'achat entre les transactions frauduleuses et les transactions normales[cite: 442, 444].
  * [cite_start]L'affluence seule ne suffit pas à expliquer la fraude, comme le montre le cas de Los Angeles (fraude élevée malgré une affluence moyenne)[cite: 412].

## 💡 Compétences démontrées
* [cite_start]Maîtrise du cycle complet de la donnée (du nettoyage à l'interprétation statistique)[cite: 188, 445].
* [cite_start]Capacité à transformer une problématique métier en tests statistiques rigoureux[cite: 162, 163].
* [cite_start]Expertise en visualisation de données pour l'aide à la décision stratégique[cite: 163].

# Projet_R
Projet d'analyse et de modélisation réalisé en Master Data Analyst à l'IAE Paris-Est
# 🕵️‍♂️ Analyse des Comportements d'Achat et Détection de Fraudes (Cosmétique de Luxe)

## 📌 Contexte du projet
Ce projet d'étude, réalisé dans le cadre de mon Master 1 Data Analyst à l'IAE Paris-Est, explore les dynamiques de vente et les incidents frauduleux dans le secteur des cosmétiques haut de gamme. 
L'objectif est d'identifier les similarités et dissimilarités de comportement selon la localisation géographique et le type de point de vente.

## 📊 Jeu de Données
**Source :** Données extraites de Kaggle portant sur la période de février à août 2025.
**Volume :** 2 133 observations internationales.
**Variables clés :** Montant d'achat, affluence quotidienne (Footfall), type de boutique (Popup, Flagship, etc.), et indicateur de fraude (Fraud_Flag).

## 🛠️ Méthodologie et Outils
**Langage :** R (Statistiques descriptives et inférentielles).
**Traitement des données :** Nettoyage et création de nouvelles variables (`store_ville` et `store_type`) pour affiner l'analyse spatiale.
 **Analyses effectuées :**
  1. **Statistiques descriptives :** Étude du panier moyen (175$) et de l'affluence moyenne (272 visiteurs/jour).
  2. **Data Visualisation :** Comparaison du taux de fraude par ville et analyse du montant d'achat via des boîtes à moustaches.
  3. **Tests Statistiques :** Tests de normalité, Test du $Khi^{2}$, Corrélation de Pearson et Test de Wilcoxon.

## 📈 Résultats et Conclusions Clés
**Géographie de la fraude :** Las Vegas présente le taux de fraude le plus élevé (8%), tandis que Paris et Genève enregistrent 0% de fraude sur l'échantillon.
 **Profils de paiement :** Hétérogénéité marquée selon les villes. La carte cadeau est privilégiée dans les zones touristiques (Paris, Tokyo), tandis que le paiement mobile domine à Hong Kong et New York.
 **Validation Statistique :**
  Le test du $Khi^{2}$ ($p-value = 0.18$) révèle qu'il n'y a **pas de dépendance significative** entre le type de boutique et la fraude.
  Le test de Wilcoxon ($p-value = 0.33$) démontre qu'il n'y a **pas de différence significative** de montant d'achat entre les transactions frauduleuses et les transactions normales.
  L'affluence seule ne suffit pas à expliquer la fraude, comme le montre le cas de Los Angeles (fraude élevée malgré une affluence moyenne).

## 💡 Compétences démontrées
Maîtrise du cycle complet de la donnée (du nettoyage à l'interprétation statistique).

Capacité à transformer une problématique métier en tests statistiques rigoureux.
Expertise en visualisation de données pour l'aide à la décision stratégique.

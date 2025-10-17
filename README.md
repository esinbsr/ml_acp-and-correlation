# Segmentation de Clients Bancaires

## Description
Ce projet vise à segmenter les clients d'une banque afin d'identifier des profils types et d'évaluer leur appétence pour la carte Visa Premier. La segmentation est réalisée grâce à des **techniques de classification non supervisée** et à l’analyse des corrélations.

## Méthodologie
1. **Prétraitement des données** : nettoyage, traitement des valeurs manquantes, normalisation.  
2. **Analyse en Composantes Principales (ACP)** : réduction de dimensionnalité et visualisation des données.  
3. **Segmentation** :
   - **K-Means** : regroupement des clients en clusters.  
   - **CAH (Classification Ascendante Hiérarchique)** : identification des groupes hiérarchiques.  
4. **Analyse des résultats** : interprétation des clusters et mise en évidence des profils clients.

## Objectif
- Identifier les profils types de clients.  
- Aider à cibler les clients avec une forte probabilité d’intérêt pour la carte Visa Premier.  

## Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Résultat attendu
- Visualisations des clusters.  
- Tableau récapitulatif des profils clients et de leur appétence.

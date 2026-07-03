# 📊 Customer Churn Analysis in Telecommunications

## 📌 Présentation du projet

La résiliation des clients (Customer Churn) représente un enjeu majeur pour les entreprises de télécommunications, car elle entraîne une perte directe de revenus et de rentabilité.

Ce projet a pour objectif d'analyser les facteurs influençant le churn, de prédire les clients susceptibles de résilier grâce au Machine Learning, puis de concevoir un tableau de bord interactif sous Power BI afin d'aider les décideurs à mettre en place des stratégies de fidélisation.

---

## 🎯 Objectifs

- Explorer et comprendre le comportement des clients grâce à une analyse exploratoire (EDA).
- Identifier les principaux facteurs de résiliation.
- Construire et comparer plusieurs modèles de Machine Learning.
- Estimer la probabilité de churn et le revenu à risque.
- Concevoir un tableau de bord Power BI interactif pour faciliter la prise de décision.

---

## 📂 Jeu de données

- **Source :** Telco Customer Churn Dataset (Kaggle)
- **Secteur :** Télécommunications
- **Nombre de clients :** 7 043
- **Variable cible :** `Churn Value`

---

# 🛠️ Technologies utilisées

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Power BI**
- **DAX**
- **Power Query**

---

# 🔍 Prétraitement et Analyse Exploratoire (EDA)

La première phase du projet consiste à comprendre les données et à préparer un jeu de données fiable pour les analyses et la modélisation.

## Prétraitement des données

- Inspection de la structure du jeu de données
- Vérification des valeurs manquantes et des doublons
- Correction des types de données
- Création de nouvelles variables (Feature Engineering)
- Nettoyage et préparation des données

## Analyse exploratoire

L'analyse s'est concentrée sur :

- Les caractéristiques démographiques des clients
- L'ancienneté des clients
- Les types de contrat
- Les services Internet souscrits
- Les méthodes de paiement
- Les dépenses mensuelles
- La valeur client (CLTV)
- L'impact financier du churn

## Validation statistique

Afin de confirmer les observations de l'EDA, plusieurs tests statistiques ont été réalisés :

- **Test du Chi²** pour mesurer la relation entre les variables catégorielles et le churn.
- **Test T de Student** pour comparer les variables numériques entre les clients résiliés et non résiliés.

---

# 🤖 Machine Learning

Une phase de Machine Learning a été développée afin de prédire le risque de résiliation des clients encore actifs.

## Étapes réalisées

- Sélection des variables explicatives
- Encodage des variables catégorielles
- Séparation des données en ensembles d'entraînement et de test
- Équilibrage des classes avec **SMOTE**
- Entraînement de plusieurs modèles
- Comparaison des performances
- Sélection du meilleur modèle
- Prédiction du risque de churn

---

## Modèles comparés

- Régression Logistique
- Random Forest
- XGBoost

Les modèles ont été évalués à l'aide des métriques suivantes :

- Recall
- F1-Score
- ROC-AUC

Le meilleur modèle a ensuite permis de calculer :

- La probabilité de churn
- Le niveau de risque
- Le revenu annuel à risque

---

# 📈 Tableau de bord Power BI

Le projet se termine par la création d'un tableau de bord interactif composé de trois pages répondant chacune à une problématique métier.

---

## 📄 Page 1 — Vue Exécutive & Impact Financier

**Question métier**

> Que se passe-t-il ?

### Principaux indicateurs

- Nombre total de clients
- Taux de churn
- Nombre de clients perdus
- Revenu annuel perdu
- CLTV moyen

### Visualisations

- Évolution du churn
- Revenu perdu par type de contrat
- Taux de churn par ancienneté
- Top des villes les plus impactées

---

## 📄 Page 2 — Facteurs & Causes de Résiliation

**Question métier**

> Pourquoi les clients résilient-ils ?

### Analyses réalisées

- Contrat le plus risqué
- Ancienneté moyenne des churners
- Service le plus associé au churn
- Méthode de paiement la plus risquée
- Principales raisons de résiliation
- Taux de churn par service
- Taux de churn par méthode de paiement

---

## 📄 Page 3 — Analyse Prédictive

**Question métier**

> Quels clients faut-il cibler en priorité ?

### Principaux indicateurs

- Nombre de clients actifs à risque élevé
- Revenu annuel à risque
- Probabilité moyenne de churn
- CLTV moyen des clients à risque

### Visualisations

- Répartition des niveaux de risque
- Relation entre probabilité de churn et revenu à risque
- Top des clients à risque
- Recommandations métier

---

# 💡 Principaux enseignements

- Les contrats **Month-to-Month** présentent le taux de churn le plus élevé.
- Les nouveaux clients sont davantage susceptibles de résilier.
- L'absence du service **Online Security** augmente significativement le risque de churn.
- Le paiement par **Electronic Check** est fortement associé au churn.
- Le Machine Learning permet d'identifier de manière proactive les clients à risque avant leur résiliation.

---

# 📊 Recommandations métier

- Prioriser les actions de fidélisation sur les clients à risque élevé.
- Cibler en priorité les clients présentant le revenu à risque le plus important.
- Encourager la migration vers des contrats annuels.
- Promouvoir le service **Online Security**.
- Favoriser les modes de paiement automatiques.

---

# 🚀 Perspectives

- Automatiser le pipeline de traitement des données.
- Mettre à jour automatiquement les prédictions.
- Déployer le modèle via une API.
- Intégrer des données en temps réel pour améliorer les performances du modèle.


# Projet Data : Kadea Telco

## 📝 Contexte

Vous venez d'intégrer l'équipe Data de **Kadea Telco**, un opérateur historique confronté à une concurrence féroce et une instabilité réseau sans précédent. La survie de l'entreprise dépend de votre capacité à transformer des montagnes de données brutes en décisions stratégiques.

Le Directeur Technique et le DG comptent sur vous pour résoudre trois crises majeures :

1. L'illisibilité des pannes réseau.
2. L'incapacité à synthétiser les pertes par région.
3. La fuite massive des clients (**Churn**).

Vous allez devoir nettoyer, croiser et automatiser des règles de gestion complexes avant de migrer toute cette intelligence vers un outil de pilotage professionnel.

---

## 🎯 Objectifs pédagogiques

Ce projet vous permet de :

* **Valider les compétences du Module 1** : Maîtrise avancée du tableur (Excel/Sheets) et initiation à la Business Intelligence (Power BI).
* **Manipuler des volumes de données massifs** : Apprendre à traiter des centaines de milliers de lignes sans erreur.
* **Traduire des règles métier complexes** : Passer d'une consigne verbale de la direction à une formule logique infaillible.

**Vous devrez :**

* Réconcilier des sources de données hétérogènes (Logs vs Registre).
* Produire une analyse macroscopique des performances réseau.
* Calculer automatiquement un plan de dédommagement financier.
* Industrialiser le reporting via un Dashboard interactif.

---

## 🛠 Technologies autorisées

| Domaine | Détails |
| --- | --- |
| **Préparation de données** | Excel / Google Sheets (Fonctions de recherche, Logique matricielle) |
| **Analyse Statistique** | Tableaux Croisés Dynamiques (TCD), Fonctions d'agrégation |
| **Business Intelligence** | Power BI (Power Query / ETL, Visualisations interactives) |

---

## 📋 Cahier des charges

### 1. Réconciliation et Nettoyage (Phase de Croisement)

* **Mission** : Utiliser les `Cell_ID` des logs bruts pour rapatrier les informations du registre de maintenance.
* **Contraintes** :
* Liaison automatique des coordonnées GPS, régions et technologies (3G/4G/5G).
* Utilisation impérative de **RECHERCHEV** (VLOOKUP) ou **RECHERCHEX** (XLOOKUP).
* Gestion propre des erreurs de recherche (`#N/A`) pour les antennes non répertoriées.



### 2. Synthèse Macroscopique (Logique Group By)

* **Mission** : Créer une vue consolidée pour le département technique.
* **Calculs attendus** :
* Somme totale des heures d'indisponibilité par Région.
* Sous-catégorisation par technologie.
* Moyenne du nombre d'abonnés impactés.


* **Livrable** : Un Tableau Croisé Dynamique (TCD) clair permettant d'identifier immédiatement la zone la plus critique.

### 3. Matrice de Rétention (Logique Algorithmique)

* **Mission** : Coder le plan de remise client via des **SI (IF) imbriqués**.
* **Règles métier à appliquer** :
* **70% de remise** : Si panne > 12h **ET** ancienneté > 5 ans.
* **45% de remise** : Si panne entre 4h et 12h **OU** (ancienneté < 5 ans **ET** forfait "Premium").
* **10% de remise** : Pour tous les clients "B2B", peu importe la panne.
* **0%** : Dans tous les autres cas.


* **Livrable** : Une colonne calculée 100% automatisée et le montant total de la perte financière pour Kadea Telco.

### 4. Dashboarding et Pilotage CODIR

* **Mission** : Migrer l'analyse vers Power BI pour mettre fin à "l'usine à gaz" Excel.
* **Fonctionnalités attendues** :
* Importation et nettoyage des données via Power Query.
* Création d'une carte géographique interactive des pannes.
* Mise en place de segments (filtres) par région, technologie et type de client.
* Visualisation dynamique de l'impact financier des remises.



---

## 📦 Livrables attendus

1. **Fichier Excel final** : Comprenant la base unifiée, les TCD de synthèse et la colonne des remises automatisée.
2. **Fichier Power BI (.pbix)** : Le dashboard interactif et fonctionnel.
3. **Rapport succinct** : Analyse des 3 régions les plus critiques et recommandation pour le DG.

---

## ⏳ Délais & Présentation

* **Date limite de rendu** : [À définir]
* **Présentation orale (15 min)** :
* **Démonstration** : Parcours du fichier Excel et du Dashboard Power BI.
* **Justification** : Explication de la formule de calcul de la matrice de rétention.
* **REX** : Difficultés rencontrées lors du croisement des données massives.



---

## 💡 Conseils de l'équipe Senior Data

> * **Vérifiez vos clés** : Assurez-vous que les `Cell_ID` sont au même format avant le VLOOKUP.
> * **Simplifiez vos SI** : Testez votre logique sur 5 lignes avant de l'étendre à 100 000.
> * **Pensez Utilisateur** : Votre dashboard Power BI doit être compréhensible par un DG en moins de 10 secondes.
> * **Sauvegardez souvent** : Les gros fichiers Excel n'aiment pas les manipulations complexes !
> 
> 

---

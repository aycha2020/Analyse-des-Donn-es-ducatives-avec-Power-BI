# Analyse-des-Donn-es-ducatives-avec-Power-BI
#  Tableau de Bord de Performance Scolaire – Power BI

##  Présentation du projet

Ce projet consiste à concevoir un **tableau de bord interactif sous Microsoft Power BI** afin d'analyser les performances scolaires, l'absentéisme des élèves, la charge de travail des enseignants et l'efficacité des cours.

L'objectif est de transformer des données brutes en informations décisionnelles permettant d'aider la direction de l'établissement à prendre des décisions basées sur les données.

---

#  Jeux de données

Le projet repose sur trois fichiers CSV :

* **students.csv** : informations sur les élèves.
* **teachers.csv** : informations sur les enseignants.
* **courses.csv** : informations sur les cours et les résultats scolaires.

---

#  Préparation des données

Le nettoyage et la transformation des données ont été réalisés avec **Power Query**.

Les principales opérations effectuées sont :

* Suppression des doublons.
* Traitement des valeurs manquantes.
* Correction des types de données.
* Standardisation des textes.
* Suppression des valeurs incohérentes (notes supérieures à 20, heures négatives, etc.).
* Création de colonnes calculées :

  * Âge des élèves.
  * Ancienneté des enseignants.
  * Année d'inscription.

---

#  Modélisation des données

Le modèle relationnel comprend les relations suivantes :

* **Students → Teachers**
* **Courses → Students**
* **Courses → Teachers**

Une table calendrier (**DimDate**) a également été créée en DAX afin de réaliser des analyses temporelles.

---

#  Mesures DAX

Les principales mesures développées sont :

* Total des élèves
* Total des enseignants
* Total des cours
* Moyenne générale
* Taux de réussite
* Élèves à risque
* Heures hebdomadaires moyennes
* Taux moyen de réalisation des cours
* Note moyenne d'évaluation des enseignants
* Nombre d'inscriptions

---

#  Tableau de bord

## Page 1 – Vue Élèves

### Indicateurs (KPIs)

* Total des élèves
* Moyenne générale
* Taux de réussite
* Nombre d'élèves à risque

### Visualisations

* Répartition des élèves par niveau scolaire et section
* Évolution des inscriptions
* Corrélation entre les absences et la moyenne générale
* Répartition des élèves par statut

---

## Page 2 – Vue Enseignants

### Indicateurs (KPIs)

* Total des enseignants
* Ancienneté moyenne
* Heures hebdomadaires moyennes
* Note moyenne d'évaluation

### Visualisations

* Répartition des enseignants par matière et type de contrat
* Distribution des notes d'évaluation
* Top 5 enseignants
* Flop 5 enseignants

---

## Page 3 – Vue Cours & Résultats

### Indicateurs (KPIs)

* Total des cours
* Taux moyen de réalisation des cours
* Taux de réussite

### Visualisations

* Répartition Réussite / Échec par matière
* Évolution des notes moyennes par semestre et par année
* Matières ayant une moyenne supérieure ou égale à 12

---

#  Principaux enseignements

Ce tableau de bord permet de :

* Identifier les élèves à risque.
* Suivre l'impact de l'absentéisme sur les résultats scolaires.
* Évaluer les performances des enseignants.
* Analyser la répartition de la charge de travail.
* Mesurer le taux de réalisation des cours.
* Suivre l'évolution des inscriptions au fil des années.
* Faciliter la prise de décision grâce à des indicateurs interactifs.

---

# 🛠 Outils utilisés

* Microsoft Power BI
* Power Query
* DAX
* Fichiers CSV

---

#  Structure du projet



---

#  Compétences développées

* Préparation et nettoyage des données
* Modélisation des données
* Création de mesures DAX
* Développement de KPIs
* Conception de tableaux de bord interactifs
* Visualisation de données
* Analyse décisionnelle (Business Intelligence)

---


## Dashboard
<img width="1123" height="634" alt="image" src="https://github.com/user-attachments/assets/91b834fe-bc04-4f08-b98b-49779441beeb" />
<img width="1136" height="639" alt="image" src="https://github.com/user-attachments/assets/1f6076fa-06ac-476f-a2c7-9f67093418de" />
<img width="1134" height="634" alt="image" src="https://github.com/user-attachments/assets/95be60c7-3bc6-408e-bd95-12dacb5cc689" />


# Ventilomètre des Étudiants 🌬️📊

## Description du projet 📝

Dans le cadre de mon projet, j'ai développé un site web permettant d'afficher et de gérer le ventilomètre des étudiants du BUT1 R&T. L'objectif de cet outil est de **cartographier les vents dans les résidences principales et secondaires des étudiants** et de stocker ces données dans une base de données.

L'application récupère les informations météorologiques à partir de fichiers CSV/JSON et d'une API météo. Elle permet non seulement de consulter les conditions météorologiques actuelles et historiques de chaque étudiant, mais aussi de visualiser un **ventilomètre collectif** qui affiche le vent médian de l'ensemble du groupe d'étudiants.

---

## 🔧 Technologies utilisées

- **Frontend** : HTML, CSS, JavaScript
- **Backend** : PHP
- **Base de données** : Fichiers CSV/JSON et base de données MySQL
- **Serveur** : Apache
- **API Météo** : Récupération des données météorologiques via une API externe

---

## ⚙️ Fonctionnalités principales

### 1. **Gestion des données météorologiques 🌦️**
Les données sur le vent des résidences des étudiants sont récupérées à partir de fichiers **JSON**. Ca permet de collecter les informations sur les conditions météorologiques pour chaque résidence, tant principale que secondaire.

### 2. **Saisie des données 📝**
Les informations concernant les étudiants (nom, prénom, adresses de leurs résidences principale et secondaire) sont saisies via un fichier **CSV**. Ensuite, l'application interroge une **API météo** pour récupérer les données météorologiques du jour pour chaque résidence.

### 3. **Ventilomètre individuel et collectif 📊**
Chaque étudiant dispose de son propre ventilomètre, avec un historique des conditions météorologiques dans ses résidences. Un ventilomètre **collectif** affiche également le vent médian de l'ensemble des étudiants, permettant une vue d'ensemble des conditions météo dans le groupe.

### 4. **Interface Web et Mobile 📱💻**
J'ai développé une application web qui est également **responsive** pour être utilisée sur mobile. L'interface permet aux utilisateurs de saisir, consulter et manipuler facilement les données météorologiques des étudiants.

---

## 🚀 Étapes de développement

### Section 1 : Mise en place de l’environnement de développement 🛠️
- Installation d'un serveur web **Apache** sur une machine virtuelle.
- Choix du langage pour le développement backend : **PHP**.

### Section 2 : Réalisation du projet 💻
- **Algorithmique** : Développement de scripts serveur pour gérer les données et interagir avec l'API météo.
- **Technologies Web** : Création de l'interface utilisateur avec **HTML**, **CSS**, et **JavaScript**.
- **Base de données** : Manipulation des données dans des fichiers CSV/JSON et dans une base de données MySQL (ajout, modification, suppression).

### Section 3 : Formation des utilisateurs 🎓
Une fois le développement terminé, une **session de formation** a été organisée pour les utilisateurs en français et en anglais. Une **documentation en anglais** a également été rédigée pour faciliter l’utilisation de l’application par des utilisateurs anglophones.

---

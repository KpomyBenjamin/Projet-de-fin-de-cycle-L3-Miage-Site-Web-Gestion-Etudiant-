# Gestion d'école

Projet de fin de cycle réalisé dans le cadre de ma Licence 3 MIAGE.

## Description

Cette application web permet de gérer les étudiants d'une école.

Elle propose notamment :

- Authentification des utilisateurs
- Authentification administrateur
- Inscription des étudiants
- Gestion des étudiants
- Ajout d'un étudiant
- Modification d'un étudiant
- Suppression d'un étudiant
- Affichage des informations des étudiants
- Gestion des photos des étudiants
- Gestion des utilisateurs et administrateurs

## Technologies utilisées

- PHP
- MySQL
- HTML5
- CSS3
- Bootstrap
- Font Awesome
- Apache

## Architecture du projet

Programme/
│
├── Authentification/
│   ├── Model/
│   ├── View/
│   └── Controler/
│
├── EspaceEtudiant/
│   ├── Model/
│   ├── Controller/
│   └── Vue/
│
├── gestionecole.sql
│
└── README.md

# Base de données

La base de données utilisée est gestionecole.

Elle contient notamment les tables :

users
admin
etudiant

# Fonctionnement

L'application distingue deux types d'utilisateurs :

# Étudiant

L'étudiant peut consulter ses informations.

# Administrateur

L'administrateur peut :

consulter la liste des étudiants ;
ajouter un étudiant ;
modifier un étudiant ;
supprimer un étudiant.

# Projet
Projet de fin de cycle — Licence 3 MIAGE
Réalisé dans le cadre de ma formation en informatique / MIAGE.

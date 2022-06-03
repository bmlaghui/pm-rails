# Project Managment APP
Ce projet a été développé dans le cadre du `3ème projet d'expertise` durant ma formation en M2 Expert IT big data & application intelligentes.

Ce projet est développé en RUBY ON RAILS

## How to install ?
***
After cloning the repo in your local computer, execute this code in the terminal:
```
$ bundle install
$ rails db:migrate
$ rails server
```
## MCD
***
![Alt text](mcd.jpg?raw=true "Title")

## SCREEN SHOTS 
***
### Connexion à l'application
![Alt text](connexion.PNG?raw=true "Title")
### Liste des projets
![Alt text](projects.PNG?raw=true "Title")
### Ajout d'un projet
![Alt text](newproject.PNG?raw=true "Title")
### Modification d'un projet
![Alt text](editproject.PNG?raw=true "Title")
### Détails d'un projet
![Alt text](projectdetails.PNG?raw=true "Title")
### Modification d'une tâche
![Alt text](update task.PNG?raw=true "Title")

## Gems utilisés
***
### devise
pour la gestion de l'authentification
### sqllite3
la Base de données pour l'ORM ACTIVE RECORD
### nested_scaffold
Pour assurer la relation entre les tables project et task (notion de cl étrangère avec l'ORM)
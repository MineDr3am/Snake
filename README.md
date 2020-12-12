

# Snake version "Nokia je te retrouve"

## Introduction
Ce projet git est un projet mené par Théophile, Luiza et moi quand nous étions élève de terminal S. Il s'agit d'un projet Baccalauréat pour l'option Information Science du Numérique (ISN). Il fallait mener un projet sous Java avec les logiciels Processing. Nous avons décidé de créer un jeu Snake comme on peut retrouver dans le Nokia3310. Vous pouvez retrouver le projet java sous Processing [ici](#). Vous pouvez jouer sur [http://46.101.102.214:8080](http://46.101.102.214:8080)

## Installation

 1. Installer [docker](https://docs.docker.com/engine/install/)
 2. Récupérer le projet: `git clone https://github.com/MineDr3am/Snake.git`
 3. Aller dans le dossier: `mkdir Snake`
 4. Créer l'image docker avec le dockerfile: `docker build -t snake:v1 .`
 5. Lancer le container docker: `docker run --name snake -d -p 8080:80 snake:v1`
 6. Aller dans http://localhost:8080 pour voir le site tourner.

## Version du projet
- [X] v1: Initialisation des valeurs:
	- Board
	- Snake
	- Food
	- Score
	- EndGame
	- Move & Agrandissement
- [X] v2: Déployer avec Docker
- [ ] v3: Ajout d'un enregistrement de score:
	- SQLite
	- Formulaire de pseudo
	- Ladderboard
- [ ] v4: Changement du Snake avec les images d'avant
- [ ] v5: Ajout des musiques et EasterEgg

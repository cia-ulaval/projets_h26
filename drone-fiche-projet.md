

# Compétition de Drone Laser Tag 🚁

## Fiche d'Identité

* **Type de projet :** Projet du Club
* **Team Lead :** Anthony Lavertu
* **Partenaire Académique/Industriel :** Philippe Giguère
* **Effectif recherché :** 5 membres
## Profils et rôles recherchés

* **GEL / GIF (x2)**
  S’occuper de la communication entre le drone, l’ordinateur central et toutes les pièces du pipeline (C, Python, autres). Optimisation et minimisation de la latence de transmission.

* **Simulation (x2)**
  Concevoir une simulation du système et des drones avec Isaac Sim (Python).

* **IA / Code (x1)**
  Concevoir un détecteur d’objets pour détecter les drones ennemis et estimer leur orientation (Rust).

* **Pilotes (x3)**
  Tests, validation et opérations en conditions réelles.

## Description du Projet

L'idée est de faire une compétition inter universitées de conduite de drone automatique. Ça va être comme les jeux de lazer tag, mais avec des drones piloté par un IA. L'objectif de la session est de consevoir le système de lasers de manière à ce qu'il puissent s'ajouter sur des drones et qu'ils soient indépendant afin d'éviter la triche. Le système devra :

* Envoyer des lasers
* Avoir un capteur 180° qui recoit les rayons lasers
* Avoir un processeur on board (et le programme) qui process l'info
* Avoir un émetteur qui envoit les hits à un ordinateur central qui pourra faire un leaderboard (nombre de lazer envoyé, nombre de laser reçu)
* Le système doit être production ready, donc avec un support standard pour le fixer sur les drones et un PCB custom (pas un Arduino ou autre)
* Avoir un receveur connecté à l'ordinateur centrale qui permet de recevoir les stats
* Un programme dans l'ordinateur centrale qui garde l'états de la partie pour éviter la triche et peut montrer le leaderboard
* Si on a le temps, peut-être mettre un système pour déterminer la hauteur du drone et pénaliser si trop haut
* Si on a le temps, faire un kill switch controlable par le game master (l’arbitre) en cas de problèmes

## Objectifs & Livrables

* **Objectif principal :** Développer un système laser production ready pouvant être installé sur n'importe quel drone de compétition.
* **Livrables attendus :**

  * Système laser avec capteurs 180° fonctionnel
  * PCB custom et programme embarqué
  * Logiciel central de gestion de parties et leaderboard
  * Supports mécaniques et boîtier professionnel


## Conditions d’engagement

* Disponibilité exigée durant toute l’année 2026 (été et session d’automne incluses)
* Engagement minimum de 5 heures par semaine
* Projet compétitif : un profil sérieux, motivé et engagé est requis

## Technologies & Compétences Visées

* **Matériels :** Drone FPV, composants laser IR, microcontrôleurs, PCB custom
* **Compétences :** Conception optique, électronique embarquée, programmation bas niveau, design mécanique, prototypage rapide

## Pourquoi rejoindre ce projet ?

Tu vas aimer ce projet si :

* Tu veux participer à la création d'une compétition technologique unique entre universités
* Tu aimes travailler sur un projet concret alliant hardware et software
* Tu veux développer des compétences en prototypage et conception de systèmes complexes
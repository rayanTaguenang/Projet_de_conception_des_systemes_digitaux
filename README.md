# Contrôle Automatique des Barrières et Feux de Passage à Niveau

## Description

Ce projet simule et contrôle automatiquement les **barrières de sécurité** et les **feux de signalisation** d’un passage à niveau pour trains et voitures.
L’objectif est d’assurer la **sécurité des véhicules et des piétons** tout en automatisant la gestion du trafic lors de l’approche d’un train.

Le système détecte l’arrivée d’un train, déclenche les signaux visuels (feux rouges clignotants) et abaisse les barrières pour bloquer la circulation automobile. Une fois le train passé, les barrières se relèvent et la circulation reprend normalement.

---

## Fonctionnalités

* Détection automatique d’un train (via capteurs réels).
* Gestion des feux de signalisation :

  * Feux rouges clignotants pour alerter les voitures.
  * Feux verts pour autoriser la circulation.
* Commande automatique des barrières :

  * Abaissement à l’approche d’un train.
  * Remontée après le passage.
* Simulation en temps réel.
* Code modulaire et facilement adaptable.

---

## Technologies utilisées

**Langage** : C / VHDL 
  **Matériel** :

  * Carte DE1-SoC Cyclone V de chez Altera.
  * Capteurs ultrasons * 4.
  * Servomoteurs pour les barrières.
  * LEDs rouge et verte.
  * Buzzer * 2.
  * Cable de connexion.
  * Servomoteur
* **Logiciels** :

  * Quartus II / ModelSim (pour simulation VHDL).
  * Arduino IDE (si version Arduino).
  * Simulation matérielle.

---


## Auteurs
**Rayan** – Développement, conception et implémentation.

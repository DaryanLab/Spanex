# Spanex
Gestion d'un spa maçonné via un automate Siemens S7-200, une HMI affichant me pH, l'ORP, la température de l'eau, de la PaC, des moteurs des pompes le tout en RS485.

<img width="1239" height="929" alt="image" src="https://github.com/user-attachments/assets/488b89d3-cade-40ed-b35d-5db0a76c2c82" />

<img width="697" height="929" alt="image" src="https://github.com/user-attachments/assets/8739f900-a03d-472d-95f7-70d9902c9c6c" />


---

Industrial SPA automation and supervision system based on Siemens S7-200 SMART PLC and HMI.

## Overview

Plateforme d'automatisation et de supervision pour Spa

Spanex est une solution complète de pilotage et de supervision développée autour d'un automate Siemens S7-200 SMART et d'une interface opérateur (IHM).

Le système permet de gérer automatiquement l'ensemble des fonctions d'un spa :

- Filtration
- Chauffage
- Traitement de l'eau
- Régulation du pH
- Mesure ORP / Redox
- Gestion du niveau d'eau
- Jets hydromassants
- Soufflerie d'air
- Éclairage
- Alarmes et sécurités

---

## Fonctionnalités

### Gestion de la filtration

- Cycles automatiques
- Gestion été / hiver
- Surveillance du fonctionnement
- Historisation des temps de marche

### Gestion du chauffage

- Contrôle de la température d'eau
- Surveillance des consignes
- Protection des équipements

### Traitement de l'eau

- Mesure pH
- Mesure ORP (Redox)
- Calibration des sondes
- Injection automatique des correcteurs

### Gestion des équipements

- Jets hydromassants
- Soufflerie d'air
- Éclairage
- Pompes auxiliaires

### Supervision

- Interface opérateur tactile
- Réglage des paramètres
- Visualisation des alarmes
- Historique de fonctionnement

### Communication

- Modbus RTU RS485
- Capteurs intelligents
- Extensions futures IoT

---

## Matériel utilisé

### Automatisme

- Siemens S7-200 SMART

### Interface opérateur

- IHM industrielle

### Capteurs

- Sonde pH
- Sonde ORP
- Capteurs de température
- Capteurs de niveau
- Capteurs de pression

### Communication

- Modbus RTU
- RS485

---

## Fonctions avancées

- Comptage des heures de fonctionnement
- Surveillance thermique des moteurs
- Gestion des défauts
- Acquittement des alarmes
- Paramétrage utilisateur
- Gestion des saisons été / hiver

---

## Évolutions prévues

- Dashboard Web
- MQTT
- Home Assistant
- Supervision à distance
- Historisation Cloud
- Notifications automatiques
- Analyse énergétique

---

## Structure du projet

```text
PLC/
├── Projet Siemens S7-200 SMART

HMI/
├── Projet Interface Opérateur

Docs/
├── Documentation
├── Cartographie Modbus
├── Liste des Entrées/Sorties

Images/
├── Captures d'écran
├── Schémas

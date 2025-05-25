# Smart Irrigation System Using IoT

## Description

Ce projet met en œuvre un système d'irrigation intelligent basé sur l'Internet des Objets (IoT), conçu pour optimiser l'utilisation de l'eau en agriculture. Il surveille en temps réel l'humidité du sol et la température ambiante afin de contrôler automatiquement une pompe d'irrigation.

Le système combine :
- Des capteurs (DHT11 pour température/humidité, capteur d'humidité de sol)
- Un microcontrôleur NodeMCU ESP8266 pour la collecte et l'envoi des données
- Un backend web pour le stockage et la gestion des données
- Une application Android pour la surveillance et le contrôle à distance

---

## Fonctionnalités

- Lecture en temps réel des données de température, humidité et humidité du sol
- Contrôle à distance de la pompe via une application Android
- Envoi et stockage des données sur un serveur distant (via PHP API et Google Apps Script)
- Interface utilisateur Android affichant les données et permettant le contrôle manuel

---

## Matériel Utilisé

- NodeMCU ESP8266
- Capteur DHT11 (température et humidité)
- Capteur d'humidité de sol analogique
- Module relais 5V pour commande de pompe
- Pompe d'irrigation électrique

---

## Installation

1. Connecter les capteurs et le relais aux pins du NodeMCU (voir schéma dans le dossier documentation)
2. Flasher le firmware Arduino disponible dans le dossier `ArduinoCode`
3. Déployer les scripts PHP sur un serveur web ou utiliser Google Apps Script API pour le backend
4. Installer et configurer l'application Android avec les bonnes URLs de backend

---

## Utilisation

- Lancer le système Arduino
- Ouvrir l'application Android pour visualiser les données en temps réel
- Contrôler manuellement la pompe via l'application

---

## Améliorations futures

- Automatisation complète basée sur seuils d'humidité
- Visualisation graphique des données historiques
- Sécurisation des communications API
- Optimisation énergétique du NodeMCU

---

## Liens utiles

- [Code source Arduino](./ArduinoCode)
- [Code source Android](./AndroidApp)
- [Backend PHP](./BackendPHP)

---

## Auteur

Youness Mchaar  
[GitHub](https://github.com/yunesmchaar) | [LinkedIn](https://www.linkedin.com/in/youness-mchaar)

---

## Licence

Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.


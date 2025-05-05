# Configuration-d-un-r-seau-d-entreprise-avec-deux-sites-WAN-

## 📘 Description

Ce projet simule l'infrastructure réseau de deux sites d'une entreprise connectés via un réseau WAN. Il a été réalisé à l'aide de Cisco Packet Tracer 

## 🏢 Architecture

- **Entreprise 1 (Siège)** :
  - Réseau local : `192.168.1.0/24`
  - Passerelle : `192.168.1.254`
  - Équipements : 1 routeur, 1 switch, 2 PC, 1 serveur

- **Entreprise 2** :
  - Réseau local : `192.168.2.0/24`
  - Passerelle : `192.168.2.254`
  - Équipements : 1 routeur, 1 switch, 2 PC

- **Connexion WAN** :
  - Réseau : `10.0.0.0/8` (liaison série entre les deux routeurs)

## 🖧 Objectifs pédagogiques

- Configurer un réseau LAN pour chaque site
- Établir une connexion WAN entre les sites
- Assurer la communication entre tous les postes
- Mettre en œuvre une passerelle et un routage correct
- Ajouter un serveur local et permettre l'accès distant

## 🧰 Technologies et outils

- **Cisco Packet Tracer**
- Routage statique (ou dynamique selon les variantes)
- Liaison série DCE/DTE
- PING et simulation ICMP

## ✅ Tests réalisés

- Ping entre les postes des deux entreprises : **réussi**
- Accès au serveur de l’entreprise 1 depuis entreprise 2 : **réussi**
- Vérification du routage et de la connectivité WAN : **ok**

## 📌 Auteur

Projet réalisé par **[hassan ibrahim]**  
 


---


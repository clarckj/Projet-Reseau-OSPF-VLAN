# Projet Réseau OSPF & VLAN (Simulation Packet Tracer)

## Description
Ce projet est une simulation d’un réseau d’entreprise incluant :
- Routage dynamique avec **OSPF**
- Sécurisation des routeurs (mot de passe + **SSH**)
- Mise en place de **VLANs** et trunking
- Segmentation en plusieurs zones réseau
- Connexion simulée vers Internet

## Topologie
![Schéma du réseau](docs/topology.png)

## Fonctionnalités
- VLAN 2 : Clients E-commerce
- VLAN 3 : Autres clients
- VLAN 99 : Administration
- Routage dynamique entre zones via OSPF
- Accès sécurisé aux routeurs via SSH

## Utilisation
- Ouvrir le fichier `.pkt` avec Cisco Packet Tracer
- Vérifier la connectivité avec des pings inter-VLAN
- Tester la connexion SSH sur le routeur principal
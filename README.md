🚀 Projet Ansible : Déploiement d’un site web avec Nginx
📌 Objectif

Ce projet a pour but de créer un playbook Ansible capable de :

Installer et configurer un serveur web Nginx

Déployer un site web HTML

S’assurer que le service Nginx reste actif

Utiliser des variables et un template Jinja2 pour automatiser le contenu de la page

🏗️ Infrastructure

Le projet repose sur deux machines :

Serveur : machine où Ansible est installé

Target : machine cible recevant la configuration

Les deux machines sont situées sur le même réseau host-only (192.168.159.0).

🔐 Configuration SSH

Création d’une clé SSH sur la machine serveur

Copie de la clé publique sur la machine cible pour permettre une connexion sans mot de passe

Test réussi : la connexion SSH fonctionne sans demande d’authentification

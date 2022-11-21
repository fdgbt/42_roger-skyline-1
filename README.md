# 42_roger-skyline-1
This project follows the 'Init' project, where some of basics commands and first reflexes in system and network administration are learned.  
This one will be a concrete example of the use of those commands and will conclude by starting a web server. 

# Expected Result
All the commands and scripts used in this project are uploaded in this repository.  
They are structured following the subject structure.  
The complete process is described in a documentation that I initiated.

# OS Specification
For this project, the choice of the Operating System is completely free inside the Linux family.  
It has been firstly realized with the Arch Linux OS.  
This was a good choice in term of pedagogy as you must go (very much) deaper with the OS installation and settings.  
But the learning curve for this advanced OS has been really sub-estimate from my part, and above all, taking much more time than expected.  
To avoid bad surprise in evaluation and ensure deadlines, the decision has be taken to switch back to the Debian OS.  
It had the effect to appreciate much more the work of simplification carried out on this kind of Linux distro (like Debian / Ubuntu).

# Special Docs
Following the great success of the initiative taken in the 'Init' project, a unique document (two in reality) has been created for this project, starting from scratch.  
In these rare documents you can follow the subject with a reminder for all notions learned, but also explanations for each scripts/commands.  
It has been designed to be very complete in terms of informations, and represents dozens of hours of research and writing.  
It takes the form of a tutorial of 85 pages for the Arch Linux OS, and an other one of 30 pages for Debian OS.  
Each document allows you to be guided step by step and to complete the project from A to Z.  
They can be shared individually upon request.  

I would like to thanks a lot the 42 peers (and friends) who helped me to produce these documents: Julien B., Benjamin W., Sven B., Gautier L. and Radhoin H.  

Unfortunately only French is available for now, the content is organised as below:

## Table des matières

### Remerciements
### Versions du document
### Table des matières
### Introduction
### V.1 Soyons plus que copain
Installer une VM à 42 (Mac OS X)  
Installer VirtualBox  
Installer une VM dans VirtualBox  
### V.2 Partie VM
Installer Arch Linux dans la VM  
- Changement de la disposition du clavier  
- Vérification la connexion au réseau  
- Mise à jour de l’heure du système  
- Partitionnement des disques  
Partitionnement des disques (autre possibilité)  
- Formatage des partitions  
- Montage les partitions  
- Sélection du miroir  
- Configuration du système  
A faire une fois Arch Linux installé  
Stockage de la VM  
### Partie Réseau et Sécurité
Créer un utilisateur non root pour se connecter et travailler  
Utiliser sudo pour pouvoir, depuis cet utilisateur, effectuer les opérations demandant des droits spéciaux  
Ne pas utiliser le service DHCP  
Configurer la VM afin qu’elle ait une IP fixe (statique) et un Netmask en /30  
Changer le port par défaut du service SSH  
L’accès SSH DOIT se faire avec des publickeys  
L’utilisateur root ne doit pas pouvoir se connecter en SSH  
Mettre en place des règles de pare-feu (firewall) sur le serveur avec uniquement les services utilisés accessible en dehors de la VM  
Mettre en place une protection contre les DOS (Denial Of Service Attack) sur les ports ouverts de la VM  
Dé-bannir une IP de l'un de vos jails  
Bannir manuellement une IP sur l'un de vos jails  
limit  
Mettre en place une protection contre les scans sur les ports ouverts de la VM  
Port Scan Attack Detector: PSAD  
Arrêter les services dont il n’y a pas besoin pour ce projet  
Réaliser un script qui met à jour l’ensemble des sources de package, puis des packages  
Créer une tâche planifiée pour ce script une fois par semaine à 4h00 du matin et à chaque reboot de la machine  
Réaliser un script qui permet de surveiller les modifications du fichier /etc/crontab et envoie un mail à root si celui-ci a été modifié  
Créer une tâche planifiée pour script tous les jours à minuit  
### VI.1 Partie Web
### VI.2 Partie Déploiement

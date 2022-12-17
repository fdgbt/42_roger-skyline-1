# 42_roger-skyline-1
This project follows the 'Init' project, where some of basics commands and first reflexes in systems and networks administration are learned.  
This one will be a concrete example of the use of those commands and will conclude by starting a web server. 

# Expected Result
All the commands and scripts used in this project are uploaded in this repository.  
They are structured following the subject structure: VM Part, Network and Security Part, Optionnal Part (Web and Deployment Part).  
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
They can be shared upon request.  

I would like to thanks a lot the 42 peers (and friends) who helped me to produce these documents: Julien B., Sven B., Benjamin W., Gautier L. and Radhoin H.  

Unfortunately only French is available for now, the content is organised as below:

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
1 Créer un utilisateur non root pour se connecter et travailler  
2 Utiliser sudo pour pouvoir, depuis cet utilisateur, effectuer les opérations demandant des droits spéciaux  
3 Ne pas utiliser le service DHCP, configurer la VM afin qu’elle ait une IP fixe (statique) et un Netmask en /30  
4 Changer le port par défaut du service SSH  
5 L’accès SSH DOIT se faire avec des publickeys  
6 L’utilisateur root ne doit pas pouvoir se connecter en SSH  
7 Mettre en place des règles de pare-feu (firewall) sur le serveur avec uniquement les services utilisés accessible en dehors de la VM  
8 Mettre en place une protection contre les DOS (Denial Of Service Attack) sur les ports ouverts de la VM  
- Dé-bannir une IP de l'un de vos jails  
- Bannir manuellement une IP sur l'un de vos jails  
- limit  

9 Mettre en place une protection contre les scans sur les ports ouverts de la VM  
- Port Scan Attack Detector (PSAD) / portSentry  

10 Arrêter les services dont il n’y a pas besoin pour ce projet  
11 Réaliser un script qui met à jour l’ensemble des sources de package, puis des packages  
12 Créer une tâche planifiée pour ce script une fois par semaine à 4h00 du matin et à chaque reboot de la machine  
13 Réaliser un script qui permet de surveiller les modifications du fichier /etc/crontab et envoie un mail à root si celui-ci a été modifié  
14 Créer une tâche planifiée pour script tous les jours à minuit  
### VI.1 Partie Web
Mettre en place un serveur web qui doit être disponible sur l’IP de la VM ou un host  
Packages: Nginx / Apache  
Mettre en place du SSL auto-signé sur l’ensemble des services  
Mettre en place une page vitrine  
### VI.2 Partie Déploiement
Proposer une solution fonctionnelle d’automatisation de déploiement  
- Bare Git Repository
- Hook Script
### Conclusion

# Reminder
These documents are available in French for Arch Linux (85 pages) and for Debian (30 pages).  
They can be shared upon request.

# Keywords
System & Network Administration  
Unix  
DevOps

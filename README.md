# 42_roger-skyline-1
This project follows the 'Init' project, where some of basics commands and first reflexes in systems and networks administration are learned.  
This one will be a concrete example of the use of those commands and will conclude by starting a web server. 

# Expected Result
All the commands and scripts used in this project are uploaded in this repository.  
They are structured following the subject structure: VM Part, Network and Security Part, Optionnal Part (Web and Deployment Part).  
The complete process is described in a documentation that I initiated.

# OS Specification
For this project, the choice of the Operating System is completely free inside the Linux family.  
In my case, it has been firstly realized with the Arch Linux OS.  
This was a good choice in term of pedagogy as you must go (very much) deeper with the OS installation and settings.  
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

### Thanks
### Versions of document
### Summary
### Introduction

### V.1 Be more than friend
Install a VM at 42 (Mac OS X)  
Install VirtualBox  
Install a VM in VirtualBox  

### V.2 VM Part
Install Arch Linux in the VM  
- Change the keyboard layout  
- Check network connection  
- Update the time system  
- Disk partitioning  
- Disk partitioning (alternative method)  
- Partition formatting  
- Mounting partitions  
- Mirror selection  
- System Setup  

What to do once Arch Linux is installed  
VM storage  

### Network and Security Part
1 Create a non-root user to login and to work  
2 Use "sudo" to be able, from this user, to perform operations requiring special rights  
3 Do not use the DHCP service, configure the VM so that it has a fixed IP (static) and a Netmask in /30  
4 Change the default port of the SSH service  
5 SSH access MUST be done with publickeys  
6 The root user must NOT be able to connect in SSH  
7 Set up firewall rules on the server with only the services used accessible outside the VM  
8 Set up protection against DOS (Denial Of Service Attack) on the open ports of the VM  
- Unban an IP from one of your jails  
- Manually ban an IP on one of your jails  
- limit module  

9 Set up protection against scans on open ports of the VM  
- Port Scan Attack Detector (PSAD) / portSentry  

10 Stop services not needed for this project  
11 Make a script that updates all package sources, then the packages themselves  
12 Create a scheduled task for this script once a week at 4:00 am and each time the machine reboots  
13 Create a script that monitors changes in the /etc/crontab file and sends an email to root (admin) if it has been modified  
14 Create scheduled task for this script every day at midnight  

### VI.1 Web Part
Set up a web server which must be available on the IP of the VM or a host  
Packages: Nginx / Apache  
Implement self-signed SSL on all services  
Set up a showcase page  

### VI.2 Deployment Part
Propose a functional solution to automate the deployment  
- Bare Git Repository
- Hook Script

### Conclusion

# Reminder
These documents are available in French only for Arch Linux (85 pages) and for Debian (30 pages).  
They can be shared upon request.  

# Keywords
System & Network Administration  
Unix  
DevOps  

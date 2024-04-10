# 1. Gestion des services : `systemd`
- utilisation de la commande `man systemctl` pour voir le manuel.  
 ![alt text](Image/manuel_systemctl.PNG)  

- utilisation de la commande `systemctl` pour voir les processus lancés par systemd.  
 ![alt text](Image/sortie_cmd_systectl.PNG)  

- connexion sur la Vm depuis mon ordinateur personel pour vérifier le `sshd` avec la commande `ssh -l iut 10.31.33.172`.  
 ![alt text](Image/connexion_ssh_VM.PNG)  

- arrêt de la Vm avec la commande `sudo service sshd stop` puis tentative de connexion depuis ma machine personelle avec `ssh -l iut 10.31.33.172`.  
 ![alt text](Image/connexion_ssh_stop_VM.PNG)  

- redémarrage du service `sshd` avec la commande `sudo service sshd start`

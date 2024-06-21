# Partie 1 : Gestion des utilisateurs

## Q.2.1.1 

![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/ac58f635-a64c-4022-8195-1edc5873ce23)

## Q.2.1.2 

Pour ce compte je préconise de l'ajouter dans le groupe `sudo` pour qu'il puisse effectuer des manipulation niveau administrateur temporairement
 
# Partie 2 : Configuration de SSH

## Q.2.2.1

![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/c300d5dc-19f7-4708-b336-b4c1028cfeb4)

## Q.2.2.2

![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/fb07d7ec-ec9c-4f2d-8783-cd7ba24afe7b)

## Q.2.2.3

![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/57562e70-a131-4f05-bfd0-809e860f703e)
![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/84a765c5-335d-4d42-9968-fd162202fd9f)

# Partie 3 : Analyse du stockage

## Q.2.3.1

Je n'ai pas bien compris la question  
Je dirais que les systeme de fichier actuellement monté sont du raid1 du lvm   
![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/8bee396b-be4f-48b8-b54c-75e4718ccab2)

## Q.2.3.2

ils utilisent le systeme de stockage LVM et RAID1

## Q.2.3.3

![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/03dc3aa4-8672-45c8-8913-c1d47028905c)


## Q.2.3.4

Pas répondu

## Q.2.3.5

Pas répondu

# Partie 4 : Sauvegardes

## Q.2.4.1

bareos-dir (Director) : il contrôle les autres composants, c'est lui qui s'occupe de la planification, du contrôle et du lancement des sauvegardes.  
bareos-sd (Storage Daemon) : c'est qui effectue les sauvegardes à proprement parler.  
bareos-fd (File Daemon) : peut être installé sur chaque machine à sauvegarder, il collecte les informations en sauvegarder et les envoie ensuite au `Storage Daemon`


# Partie 5 : Filtrage et analyse réseau

## Q.2.5.1

![image](https://github.com/NicoClaverie/TSSR---Checkpoint-3/assets/161337347/f84b69ef-7343-426d-a8f3-9af3260dbb2b)


## Q.2.5.2

Sont autorisé :  
- les paquets qui sont déjà associés à une connexion établie ou qui sont liés à une connexion déjà établie à passer à travers le pare-feu.
- les communications sur la loopback.
- les comunications `TCP` sur le port 22 (SSH)
- le protocol `ICMP` pour les ping
- le protocol `IpV6-ICMP` pour les ping en Ipv6

## Q.2.5.3

Sont interdit :  
- Tout les paquets entrant
- Les paquets invalide  


## Q.2.5.4

Pas répondu

# Partie 6 : Analyse de logs

## Q.2.6.1

Pas répondu


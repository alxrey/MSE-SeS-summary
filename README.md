# Résumé SeS 2021

## Liste des sujets de l'examen oral

### Buildroot

1. D’expliquer les principaux répertoires de buildroot
2. D’expliquer comment configurer, compiler buildroot, u-boot, kernel
3. D’expliquer comment le rootfs est généré
4. D’expliquer le rootfs_overlay

### u-boot

1. D’expliquer le démarrage du NanoPi
2. De connaître, expliquer les principales commandes de u-boot utilisées durant le 
démarrage
3. De savoir comment configurer u-boot
4. D’expliquer comment améliorer la sécurité de u-boot
5. De connaître les différentes étapes pour la création de l’image de u-boot.itb
6. Savoir ce que fait la commande strip sur un fichier elf
7. De connaître les différentes étapes pour la création de uImage
8. Se connaître les différents formats du kernel
9. De connaître l’utilité du Flattened Device Tree
10. De connaître de manière générale le mapping de la SDCard
11. D’expliquer le fichier boot.scr

### Compilation du noyau

1. De connaître les principaux répertoires du noyau Linux
2. De connaître les principales méthodes pour sécuriser le noyau Linux
3. D’expliquer le principe des software attacks : buffer overflow, ret2libc, ROP
4. D’expliquer le principe des protections contre les softwares attack : ASLR, PIE, canary

### Valgrind

1. De connaître les différents outils de Valgrind et leur utilisation
2. Pour un code donné avec des erreurs, savoir quel-s outil-s de Valgrind utiliser

### Hardening Linux

1. De contrôler l’intégrité d’un package, d’un programme
2. De configurer un nouveau package, programme
3. De cross-compiler un programme
4. De contrôler les services, les ports ouverts
5. De contrôler les « file systems »
6. De contrôler les permissions des fichiers, répertoires
7. De sécuriser le réseau
8. De contrôler-sécuriser les comptes utilisateurs
9. De limiter le login root
10. De sécuriser le noyau
11. De sécuriser une application
12. De contrôler le démarrage de Linux

### Filesystem

1. De connaître les différents types de systèmes de fichiers ainsi que leurs applications
2. De connaître les caractéristiques des filesystems ext2-3-4, ainsi que les commandes associées
3. D’expliquer les différents « files systems » utilisés dans les systèmes embarqués (ext2-3-4, BTRFS, F2FS, NILFS2, XFS, ZFS, …)
4. Expliquer les « files system » de type Journal, B_Tree/CoW, log filesystem
5. De connaître les caractéristiques du filesystem Squashfs, ainsi que les commandes associées
6. De connaître les caractéristiques du filesystem tmpfs, ainsi que les commandes associées
7. De connaître les caractéristiques du filesystem LUKS, ainsi que les commandes associées
8. Savoir expliquer la gestion des clés de LUKS 42. 
9. De connaître les caractéristiques du filesystem InitramFS, ainsi que les commandes associées
10. De savoir créer un initramFS


### Filesystems security

1. De connaître les « files permissions » sous Linux
2. De contrôler et sécuriser les comptes utilisateurs sous Linux
3. De connaître les real-effective userID and groupID
4. De connaître les ACL
5. De connaître les attributs particuliers des filesystems ext2-3-4
6. De rechercher des permissions de fichier faibles
7. Comment sécuriser les répertoires temporaires
8. De savoir comment les mots de passe sont mémorisés sous Linux

### Firewall Iptables

1. De connaître les principes de Netfilter, iptables
2. Savoir expliquer les notions de chain-tables
3. Savoir configurer un firewall avec Iptables
4. Connaitre les modules d’extension principaux de iptables, netfilter
5. Savoir expliquer le principe de fonctionnement de knockd et les liens avec iptables
6. Savoir expliquer le principe de fonctionnement de fwknop et les liens avec iptables

### TPM

1. Savoir expliquer le principe des chiffrements symétrique, asymétrique, fonctions de hachage, la signature digitale.
2. Connaitre les différentes implémentations des TPM (discrete, integrated, Hypervisor, Software)
3.  Connaitre l’architecture interne d’un TPM
4. Connaitre les différentes hiérarchies des TPM (endorsement, platform, owner, null)
5. Savoir créer, utiliser des clés avec un TPM 63.
6. Connaitre les commandes principales d’un TPM (pas tous les paramètres, mais savoir expliquer ce que font ces commandes, être capable de dessiner ce que font les commandes)
7. Savoir encrypter-décrypter, signer-vérifier avec un TPM
8. Savoir utiliser les registres PCR
9. Savoir sauver des données sur le TPM
10. Savoir sauver des données et les protéger avec une PCR policy
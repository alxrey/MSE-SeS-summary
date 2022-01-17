## TPM

### Savoir expliquer le principe des chiffrements symétrique, asymétrique, fonctions de hachage, la signature digitale.

#### symétrique

- Une seul clé pour crypter et décrypter
- Codage par bloc ou par bloc chainé **(figure CBC)** 
- `openssl enc -aes-256-cbc -e -in t.txt -out t.enc` //encrypt
- `openssl enc -aes-256-cbc -d -in t.enc -out t.txt`//decrypt

#### asymétrique

- Deux clés (publique et privée) clé publique disponible par des certificats (CMD pgp)
- Encrypt public -> Decrypt private => confidentialité
- Encrypt private-> Decrypt public => signature digitale

#### hash

Transforme un texte, document en un nombre de N bits unique (SHA-2, SHA-3, Blake2).

`md5sum file => a6a0e8d0522e2c5de921b1c455506320` ou `openssl dgst -md5 file MD5(file)= a6a0e8d0522e2c5de921b1c455506320`  

#### signature

En deux parties: 1. Calcul du HASH puis encryptage avec clé privée. **(figure signature)**

### Connaitre les différentes implémentations des TPM (discrete, integrated, Hypervisor, Software)

- discrete : Circuit dédié 
- integrated : Partie du $\mu C$ qui gère le TPM
- Hypervisor : virtuel fournis par personne fiable
- Software : virtuel pour faire des test pas sécurisé

### Connaitre l’architecture interne d’un TPM

**(figure internal)** 

### Connaitre les différentes hiérarchies des TPM (endorsement, platform, owner, null)

- endorsement : 
- platform
- owner
- null

### Savoir créer, utiliser des clés avec un TPM

### Connaitre les commandes principales d’un TPM (pas tous les paramètres, mais savoir expliquer ce que font ces commandes, être capable de dessiner ce que font les commandes)

### Savoir encrypter-décrypter, signer-vérifier avec un TPM

### Savoir utiliser les registres PCR

### Savoir sauver des données sur le TPM

### Savoir sauver des données et les protéger avec une PCR policy
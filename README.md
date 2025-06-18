# dev-avancee-td-note

LIEVRE Antoine 306

# Réponses

## 1.1

La taille par défaut est 2048, pour créer une clef de 4096 bits il faut faire : openssl genrsa -out server.key 4096

## 1.2

openssl rsa -in server.key -pubout -out server.pub

## 2.1

openssl genrsa -des3 -out server_des3.key 4096

## 2.2 

Pour l'extraire nous avons besoin d'indiquer une PEM pass phrase que nous avons indiqué au moment de la création de la pair de clefs

## 3.1 

C:\Users\ANTOI\Documents\TD_NOTE_DEV_AVANCEE\dev-avancee-td-note>openssl dgst -sha256 FICHIER_SOURCE.java
SHA2-256(FICHIER_SOURCE.java)= f0ee26ed46983b9e9462c2408ef813eef216de5aa7f93afaf1960c7016515e49

C:\Users\ANTOI\Documents\TD_NOTE_DEV_AVANCEE\dev-avancee-td-note>openssl dgst -md5 FICHIER_SOURCE.java
MD5(FICHIER_SOURCE.java)= 6e128b74f3c1dccdadbb6a9902047569

C:\Users\ANTOI\Documents\TD_NOTE_DEV_AVANCEE\dev-avancee-td-note>openssl dgst -sha-1 FICHIER_SOURCE.java
SHA1(FICHIER_SOURCE.java)= 44173be2ba2c36ce01b13c493bb93a25f4b0c2a2


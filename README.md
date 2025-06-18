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

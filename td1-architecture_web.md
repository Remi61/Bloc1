# Bloc1
## 1_architecture_web

## 1 - Méthodes GET et POST

Avec la méthode GET, les données à envoyer au serveur sont écrites directement dans l’URL. Dans la fenêtre de son navigateur.
La méthode POST écrit les paramètres URL dans la requête HTTP pour le serveur. Les paramètres ne sont donc pas visibles pour les utilisateurs.

La méthode POST n'est pas sécurisée ni indempotente. de plus, les données ne sont pas certaines de pouvoir être mise en cache. Contrairement a la méthode get qui est Sûr, 	
Idempotent, Peut être mis en cache. Les 2 Méthodes sont tt de même autorisée  dans les formulaires html.

## 2 – Comparaison méthodes
Méthode POST

![image](https://github.com/user-attachments/assets/b68b98d6-5dab-452f-9dac-6c65a031e074)                        


Méthode GET

![image](https://github.com/user-attachments/assets/d29f14ba-d65c-421e-b77f-83836ffa644a)


## 3 -Extensible

À partir de HTTP/1.0, les en-têtes HTTP permettent d'étendre facilement le protocole et de mener des expérimentations avec celui-ci. De nouvelles fonctionnalités peuvent même être introduites par un simple accord entre le client et le serveur à propos de la sémantique des nouveaux en-têtes.

## 4 - Sans état

Cela signifie que c'est un protocole de communication qui n'enregistre pas l'état d'une session de communication entre deux requêtes successives.

## – URL

![image](https://github.com/user-attachments/assets/7bc44a52-2068-4138-b236-1393d2cff7e5)

## 6 - Codes Status



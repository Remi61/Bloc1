

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

## 5– URL

![image](https://github.com/user-attachments/assets/7bc44a52-2068-4138-b236-1393d2cff7e5)

## 6 - Codes Status

200 : succès de la requête ;  <br>
301 et 302 : redirection, respectivement permanente et temporaire ; <br>
401 : utilisateur non authentifié ; <br>
403 : accès refusé ; <br>
404 : ressource non trouvée ; <br>
500, 502 et 503 : erreurs serveur ; <br>
504 : le serveur n'a pas répondu.

## 7 – Négociation de contenu
Lorsqu'un client souhaite obtenir une ressource, il la demande via une URL. Le serveur utilise alors cette URL pour choisir l'une des variantes disponibles. Chaque variante est appelée une représentation. Le serveur renvoie alors une représentation donnée au client.


## 10 - Headers
![image](https://github.com/user-attachments/assets/0b10ff43-5fd6-481b-9bbd-a082e62f4058)![image](https://github.com/user-attachments/assets/8cd7d64f-5e5e-43e4-b965-cdc95b44e4f2)![image](https://github.com/user-attachments/assets/00df9624-ab1a-4197-9f45-3a480dc7cbfd)

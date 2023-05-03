# trt_conseil

## Description

trt-conseil a pour but de mettre en relation des responssable de restaurent, de brasserie ou de café avec des personnes qui recherche un travail dans ce secteur

## Installation

1 Clonez le projet depuis GitHub. https://github.com/pickypou/trt_conseil.git
2 Exécutez la commande composer install pour installer les dépendances.
3 Configurez la base de données dans le fichier .env.
4 Executez dans la console la commande suivant: php bin/console doctrine:database:create pour créer  la base de données.
5 Exécutez dans la console la commande php bin/console doctrine:migrations:migrate pour créer les tables dans la base de données.

## Utilisation
Connectez-vous en tant qu'administrateur pour accéder à la page d'administration.
Dans la page d'administration, vous pouvez voir la liste des utilisateurs et leur attribuer un rôle en utilisant le formulaire.
Le ROLE_USER est donnée par défaut seule admin peut atribué le ROLE_CUSULTANT, le consultant a droit de donné les ROLE_CANDIDAT et ROLE_RECRUTEUR

## Fonctionnalités

aprés inscription un utilisateur peut choisir si il est candidat ou recruteur.
 En tant que candidat déposer un cv et on peut consulté toutes les annonces déposer et y postuler.
 En tant que recruteur vous pouvez déposer des annonces et étre mis en relation avec les candidat intéréser par votre annonce.
Aprés validation  par un consultant

 ## contact 
 en cas de problème ou pour toute amelioration vous pouver m'envoyer un email a lud@ludo.fr

Auteur
Ludovic SPYSSCHAERT

Licence
Ce projet est sous licence MIT.
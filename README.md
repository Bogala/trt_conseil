# trt_conseil

## Description

trt-conseil a pour but de mettre en relation des responssable de restaurent, de brasserie ou de café avec des personnes qui recherche un travail dans ce secteur

## Installation

1 Clonez le projet depuis GitHub. https://github.com/pickypou/trt_conseil.git
2 Exécutez la commande composer install pour installer les dépendances.
3 Configurez la base de données dans le fichier .env.
4 Executez dans la console la commande suivant: php bin/console doctrine:database:create pour créer  la base de données.
5 Exécutez dans la console la commande php bin/console doctrine:migrations:migrate pour créer les tables dans la base de données.

## Roles admin
Connectez-vous en tant qu'administrateur pour accéder à la page d'administration.
Dans la page d'administration, vous pouvez voir
- La liste des utilisateurs
-La liste des utilisateurs non validé
-Le détaile de chaques utilisatuer Validé
-Validé un compte utilisateur
-Leur attribuer un rôle en utilisant le formulaire.Seul admin peut atribué le ROEL_CONSULTANT,Le ROLE_USER  a touts les utilisateurs
-La liste de toutes les annonces posté 
-La liste des annonce non validé
-Validé une annonce
-Voir toutes les candidatures
-validé une candidature
-suprimer un compte

## ROLES consultant
les consultant sont des personnes qui sont charger de l'administration du site
Connectez-vous  pour accéder à la page d'administration.
Dans la page d'administration, vous pouvez voir
- La liste des utilisateurs
-La liste des utilisateurs non validé
-Le détaile de chaques utilisatuer Validé
-Validé un compte utilisateur
-Leur attribuer un rôle en utilisant le formulaire.ROLES-CANDIDAT ou ROLE_RECRUTEUR
-La liste de toutes les annonces posté 
-La liste des annonce non validé
-Validé une annonce
-Voir toutes les candidatures
-validé une candidature

## Fonctionnalités

A sont inscription un utilisateur peut choisir si il est candidat ou recruteur.
 #### En tant que candidat 
 -Aucune connexion possible tant que le compte n'est validé (un email et envoyer a votre adresse mail pour confirmé la validation du compte)
 -Vous pouvze déposer un cv 
 -consulté toutes les annonces en ligne
 -consulté le détail de chaque annonce
-postuler a une annonce (un email vous est envoyer pour confirmer la candidature)

#### En tant que recruteur
-Aucune connexion possible tant que le compte n'est validé (un email et envoyer a votre adresse mail pour confirmé la validation du compte)
-vous devrais métre a jour votre profile raison social, une petite description de vos spécialitées 
-desposé une annonce via un formulaire (unemail de validation et de mise en ligne vous serra envoyer)
-voir les détail des candidat qui ont postulé a votre annonce
 ## contact 
 en cas de problème ou pour toute amelioration vous pouver m'envoyer un email a lud@ludo.fr

Auteur
Ludovic SPYSSCHAERT

Licence
Ce projet est sous licence MIT.
# Tuto LAMP

Documentation technique d'une stack LAMP derrière un reverse-proxy, sous forme d'une page web unique :

**DNS → HAProxy → Apache2 → PHP-FPM → MariaDB**

## Sommaire

- Synopsis
- Architecture
- Parcours d'une requête, du navigateur à la base de données
- Fichiers de configuration
- Ports utilisés
- Dépannage

Les noms de domaine et adresses du guide sont des exemples (`exemple.fr`, plages réservées à la documentation).

## Utilisation

Ouvrir `index.html` dans un navigateur, ou servir le dossier avec n'importe quel serveur web statique.

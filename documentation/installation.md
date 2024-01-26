# Installation et configuration des différents services et modules
Ce fichier explique en détail les différentes étapes pour construire un serveur web sécuritaire à partir de zéro
## Ubuntu 22.04
### Création des utilisateurs administrateurs
Ajouter mon utilisateur et l'utilisateur de l'enseignant
```
sudo adduser Bobby
sudo adduser Charles
```
ajouter mon utilisateur et l'utilisateur de l'enseignant au groupe `sudo` 
```
sudo usermod -aG sudo Bobby
sudo usermod -aG sudo Charles
```
valider que les utilisateurs existent
```
id Bobby
id Charles
```
Me connecter en SSH avec mon nouvel utilisateur Bobby
```
su -l Bobby
```

### Tester la connexion en SSH
...

## Apache
### Installer et configurer Apache

## PHP
...

etc.

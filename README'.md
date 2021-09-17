# Script d'installation d'une SeedBox sur debian 9/10

![logo](https://raw.github.com/ouic/seedbox/master/files/ureal.png)

* Multi-utilisateurs & Multilingue automatique en fonction de l'installation du serveur
* Français, English, German, Pусский,  Español, Português
* Nécessite Debian 9/10 (64 bits) & un serveur fraîchement installé

* Inclus VsFTPd (ftp & ftps sur le port 21), Fail2ban (avec conf nginx, ftp & ssh)

Tiré du tutoriel de mondedie.fr disponible ici:

[Installer ruTorrent sur Debian {nginx & php-fpm}](https://mondedie.fr/d/10831-tuto-installer-rutorrent-sur-debian-10-nginx-php-fpm)

[Aide, support & plus si affinités à la même adresse !](http://mondedie.fr/)

**Auteur :** Ex_Rat, **modifié par :** uReaL team ([www.ureal.fr.nf](http://www.ureal.fr.nf/))


Merci aux traducteurs: Sophie, Spectre, Hardware, Zarev, SirGato, MiguelSam, Hierra

## Installation:

commande d'installaton (multilangue automatique)
```
apt-get update && apt-get upgrade -y && apt-get install git-core git lsb-release -y && cd /tmp && git clone https://github.com/ouic/seedbox && cd seedbox && chmod a+x seedbox_setup.sh && ./seedbox_setup.sh
```
![caps1](https://raw.github.com/ouic/seedbox/master/files/caps_script01.png)

Le script vous demande de créer un utilisateur, exemple :

- Utilisateur : seedbox
- Mot de passe : password

Pour gérer vos utilisateurs ultérieurement, il vous suffit de relancer le script

![caps2](https://raw.github.com/ouic/seedbox/master/files/caps_script02.png)


**Vous pouvez aussi forcer la langue de votre choix en modifiant la commande initiale avec :**
```
# Français
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --fr

# English
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --en

# Pусский  ( "д/H" или "y/n" )
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --ru

# German
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --de

# Español
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --es

# Português
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --pt

# Português do Brasil
chmod a+x seedbox_setup.sh && ./seedbox_setup.sh --ptbr
```

### Disclaimer
Ce script est proposé à des fins d'expérimentation uniquement, le téléchargement d’oeuvre copyrightées est illégal.

Merci de vous conformer à la législation en vigueur en fonction de vos pays respectifs en faisant vos tests sur des fichiers libres de droits.

### License
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)


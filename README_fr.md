# phpBB pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/phpbb.svg)](https://dash.yunohost.org/appci/app/phpbb) ![](https://ci-apps.yunohost.org/ci/badges/phpbb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpbb.maintain.svg)  
[![Installer phpBB avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpbb)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer phpBB rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Forum facile à utiliser, puissant et hautement personnalisable

**Version incluse :** 3.3.4~ynh1

**Démo :** https://www.phpbb.com/demo/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

1. L'application devra terminer le processus d'enregistrement une fois l'installation terminée en **visitant le domaine** sur lequel *phpBB* est installé.
1. Les informations d'identification de la base de données MySQL seront envoyées à la **messagerie admin**.
1. Veuillez supprimer, déplacer ou renommer le répertoire d'installation (`mv /var/www/phpbb/install /var/www/phpbb/install_old`) avant d'utiliser votre forum. Si ce répertoire est toujours présent, seul le panneau de configuration d'administration (ACP) sera accessible. 
## Documentations et ressources

* Site officiel de l'app : http://www.phpbb.com/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://www.phpbb.com/support/docs/
* Dépôt de code officiel de l'app : https://github.com/phpbb/phpbb
* Documentation YunoHost pour cette app : https://yunohost.org/app_phpbb
* Signaler un bug : https://github.com/YunoHost-Apps/phpbb_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phpbb -u https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
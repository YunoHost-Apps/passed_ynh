<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# PassED pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/passed)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/passed)

[![Installer PassED avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer PassED rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Partagez un mot de passe avec quelqu'un de façon sécurisée via la génération d'URLs à usage unique afin qu'il ne reste pas en clair dans une boîte email, ne soit pas montré au sein d'une notification d'application de messagerie, etc. 

Le mot de passe est contenu dans l'URL elle-même sous une forme chiffrée, tandis que la clé de déchiffrement stockée sur le serveur est supprimée après la première utilisation ou à l'expiration du délai indiqué.


**Version incluse :** 2024.12.29~ynh1

## Captures d’écran

![Capture d’écran de PassED](./doc/screenshots/passed_ynh.png)

## Documentations et ressources

- Documentation officielle utilisateur : <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Dépôt de code officiel de l’app : <https://git.1e99.eu/1e99/passed>
- YunoHost Store : <https://apps.yunohost.org/app/passed>
- Signaler un bug : <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
ou
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

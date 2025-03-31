<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# PassED voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/passed)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/passed)

[![PassED met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je PassED snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Geleverde versie:** 2024.12.29~ynh1

## Schermafdrukken

![Schermafdrukken van PassED](./doc/screenshots/passed_ynh.png)

## Documentatie en bronnen

- Officiele gebruikersdocumentatie: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Officiele beheerdersdocumentatie: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#configuration>
- Upstream app codedepot: <https://git.1e99.eu/1e99/passed>
- YunoHost-store: <https://apps.yunohost.org/app/passed>
- Meld een bug: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
of
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>

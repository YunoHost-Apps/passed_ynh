<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# PassED per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/passed)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/passed)

[![Instal·la PassED amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar PassED de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Versió inclosa:** 2024.12.29~ynh1

## Captures de pantalla

![Captures de pantalla de PassED](./doc/screenshots/passed_ynh.png)

## Documentació i recursos

- Documentació oficial per l'usuari: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Repositori oficial del codi de l'aplicació: <https://git.1e99.eu/1e99/passed>
- Botiga YunoHost: <https://apps.yunohost.org/app/passed>
- Reportar un error: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
o
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>

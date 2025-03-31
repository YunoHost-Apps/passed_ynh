<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# PassED YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/passed)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/passed)

[![Instalatu PassED YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek PassED YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Paketatutako bertsioa:** 2024.12.29~ynh1

## Pantaila-argazkiak

![PassED(r)en pantaila-argazkia](./doc/screenshots/passed_ynh.png)

## Dokumentazioa eta baliabideak

- Erabiltzaileen dokumentazio ofiziala: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Administratzaileen dokumentazio ofiziala: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#configuration>
- Jatorrizko aplikazioaren kode-gordailua: <https://git.1e99.eu/1e99/passed>
- YunoHost Denda: <https://apps.yunohost.org/app/passed>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
edo
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

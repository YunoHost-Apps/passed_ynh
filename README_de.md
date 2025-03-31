<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# PassED für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/passed)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/passed)

[![PassED mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie PassED schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Ausgelieferte Version:** 2024.12.29~ynh1

## Bildschirmfotos

![Bildschirmfotos von PassED](./doc/screenshots/passed_ynh.png)

## Dokumentation und Ressourcen

- Offizielle Benutzerdokumentation: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Upstream App Repository: <https://git.1e99.eu/1e99/passed>
- YunoHost-Shop: <https://apps.yunohost.org/app/passed>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
oder
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>

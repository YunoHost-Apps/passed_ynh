<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# PassED para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/passed)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/passed)

[![Instalar PassED con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar PassED de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Versión proporcionada:** 2024.12.29~ynh1

## Capturas de pantalla

![Captura de pantalla de PassED](./doc/screenshots/passed_ynh.png)

## Documentación e recursos

- Documentación oficial para usuarias: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Repositorio de orixe do código: <https://git.1e99.eu/1e99/passed>
- Tenda YunoHost: <https://apps.yunohost.org/app/passed>
- Informar dun problema: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
ou
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>

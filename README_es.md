<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# PassED para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Estado funcional](https://apps.yunohost.org/badge/state/passed)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/passed)

[![Instalar PassED con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarPassED rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Versión actual:** 2024.12.29~ynh1

## Capturas

![Captura de PassED](./doc/screenshots/passed_ynh.png)

## Documentaciones y recursos

- Documentación usuario oficial: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Documentación administrador oficial: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#configuration>
- Repositorio del código fuente oficial de la aplicación : <https://git.1e99.eu/1e99/passed>
- Catálogo YunoHost: <https://apps.yunohost.org/app/passed>
- Reportar un error: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
o
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>

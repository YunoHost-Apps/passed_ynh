<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# PassED untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![Status kerja](https://apps.yunohost.org/badge/state/passed)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/passed)

[![Pasang PassED dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang PassED secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**Versi terkirim:** 2024.12.29~ynh1

## Tangkapan Layar

![Tangkapan Layar pada PassED](./doc/screenshots/passed_ynh.png)

## Dokumentasi dan sumber daya

- Dokumentasi pengguna resmi: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- Dokumentasi admin resmi: <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#configuration>
- Depot kode aplikasi hulu: <https://git.1e99.eu/1e99/passed>
- Gudang YunoHost: <https://apps.yunohost.org/app/passed>
- Laporkan bug: <https://github.com/YunoHost-Apps/passed_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/passed_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
atau
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>

# AYNI Releases

This is the official download channel for **AYNI**, the offline AI support app
for children with autism spectrum disorder. It is a self-hosted
[F-Droid](https://f-droid.org) repository: signed APKs and a signed index.

A project of WIE UTP — the WIE Student Branch at Universidad Tecnológica del Perú.

## Install AYNI on a tablet

1. Install the **F-Droid** client from [f-droid.org](https://f-droid.org).
2. Add this repository in F-Droid under Settings → Repositories → **+**:

   ```
   https://wie-utp.github.io/ayni-releases/repo
   ```

   Or scan this QR code (it includes the repo fingerprint):

   <!-- Add repo-qr.png here once generated via: fdroid server -->
   ![Add AYNI repo](repo-qr.png)

3. Search for **AYNI** and install.

## Updates

F-Droid checks this repo periodically. When a new version is available it shows
an update banner. Tap Update, it downloads over Wi-Fi in a few seconds and
installs over the existing app. Settings and data are kept.

## What's here

```
repo/
├── index-v1.jar        signed repo index (F-Droid reads this)
├── ayni-<version>.apk  signed APK builds
└── ...
```

## License

Apache 2.0.

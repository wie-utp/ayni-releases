# AYNI Releases

This is the official download channel for **AYNI**, the offline AI support app
for children with autism spectrum disorder. It is a self-hosted
[F-Droid](https://f-droid.org) repository: signed APKs and a signed index, no
source code. The source lives in a separate private repo.

A project of the WIE Student Branch at Universidad Tecnológica del Perú, funded
by EPICS in IEEE.

## Install AYNI on a tablet

1. Install the **F-Droid** client from [f-droid.org](https://f-droid.org).
2. Add this repository in F-Droid → Settings → Repositories → **+**:

   ```
   https://wie-utp.github.io/ayni-releases/repo
   ```

   Or scan this QR code (it includes the repo fingerprint, so F-Droid trusts it
   automatically):

   <!-- Generated once the repo is live: in F-Droid, open the repo and tap the
        share/QR icon, or run `fdroid server` tooling. Drop the PNG here. -->
   ![Add AYNI repo](repo-qr.png)

3. Search for **AYNI** in F-Droid and install.

## Updates

F-Droid checks this repo periodically. When a new version is published it shows
an update banner. Tap **Update**, it downloads over Wi-Fi in a few seconds and
installs over the existing app. Your settings and data are kept.

## What's here

```
repo/
├── index-v1.jar        signed repository index (F-Droid reads this)
├── ayni-<version>.apk  signed application packages
└── ...
```

## Verifying

Every APK is signed with the stable AYNI release key, and the index is signed so
the F-Droid client can confirm these files came from the project. The repo
fingerprint is shown in F-Droid when you add the repository.

## License

The app is Apache 2.0. See the source repository for details.

# AYNI Releases

Official download channel for **AYNI**, the offline AI support app for children with
autism spectrum disorder. This is a self-hosted [F-Droid](https://f-droid.org) repository:
signed APKs and a signed index. Source code lives in a separate private repo.

A project of WIE UTP, the WIE Student Branch at Universidad Tecnologica del Peru.

---

## Install AYNI on a tablet

1. Install the **F-Droid** client on your Android device from [f-droid.org](https://f-droid.org).

2. Open F-Droid, go to **Settings** > **Repositories** > tap the **+** button and enter:

   ```
   https://wie-utp.github.io/ayni-releases/repo
   ```

   Or scan this QR code directly in F-Droid to add the repo (the fingerprint is embedded):

   ![Add AYNI F-Droid repo](repo-qr.png)

3. Search for **AYNI** and tap Install.

## Updates

F-Droid checks this repo periodically. When a new version is available, it shows an update
notification. Tap Update, the APK downloads over Wi-Fi in a few seconds and installs over the
existing app. Settings and data are preserved.

## What is here

```
repo/
├── index-v1.jar        signed repo index (F-Droid reads this)
├── app-release.apk     signed application builds
└── ...
```

## Repo fingerprint

For manual verification, the repo signing key fingerprint is:

```
24725C42938F2BEC551ABE958D043B6BD3FF500146011B7E204D41C34FBA4D8B
```

## License

Apache 2.0.

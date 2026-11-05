# Hazina for Android

Signed Android builds of Hazina, a shelf for every game you own on PlayStation, Xbox, Switch and PC, with price-drop alerts for the ones you want.

This repository only holds release builds. The app's source code is kept in a separate repository.

**Latest build:** [hazina.apk](https://github.com/Garv2003/hazina-releases/releases/latest/download/hazina.apk)

## Install

1. Open the link above on your Android phone (Android 7.0 or newer, 64-bit) and download `hazina.apk`.
2. Open the downloaded file. If Android asks, allow your browser to install unknown apps.
3. Google Play Protect may say it doesn't recognise the developer. Tap "More details", then "Install anyway".

## Update

Download the latest build and install it over the old one. Your sign-in and data stay.

## Verify a download

Every build is signed with the same key, and each release lists the APK's SHA-256 checksum. To check a download:

```sh
shasum -a 256 hazina.apk
```

## Privacy

The app talks only to the Hazina server. Your collection, wishlist and prices are stored there; nothing is sold or shared.

## License

All rights reserved. You may install the app for your own personal use; you may not copy, re-host, sell or modify it. See [LICENSE](LICENSE).

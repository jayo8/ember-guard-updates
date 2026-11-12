# Ember Guard updates

This repository only hosts **release builds** of Ember Guard, a private, on-device screen-time and protection app for Android. There is no source code here.

## Install
1. On your phone, open the [latest release](https://github.com/jayo8/ember-guard-updates/releases/latest) and download `EmberGuard-*.apk`.
2. Open the file and allow your browser or Files app to install apps if Android asks.
3. Tap Install.

## Update
Inside the app: **More > Updates**, paste this address, tap Save, then Check:

```
https://github.com/jayo8/ember-guard-updates/releases/latest/download/version.json
```

Ember Guard only installs an update if the file's SHA-256 matches `version.json` and it is signed with the same key as the version you already have. Android asks you to confirm the install.

# Dayline for Android

A WebView wrapper around the Dayline web app (bundled offline in `app/src/main/assets/www`).

## Get the APK (no Android Studio needed)
1. Create a new GitHub repository and upload everything in this folder (keep `.github/`).
2. Open the **Actions** tab → **Build APK** → wait for the green check.
3. Open the run, download the **Dayline-apk** artifact, unzip it, and install `app-debug.apk` on your phone (allow "install unknown apps").

## Or with Android Studio
Open this folder, let it sync, then **Build → Build APK(s)**.

Notes: the app keeps its data on-device (localStorage). The only network use is the Google Fonts
stylesheet; offline it falls back to system fonts.

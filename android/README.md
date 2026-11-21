# CURLING ARENA 3D — Android

This folder contains a native Android WebView shell for the existing 3D browser game.

## Build

The GitHub Actions workflow builds an installable debug APK on pushes to `main` that change this folder.

The APK is uploaded as the workflow artifact named `curling-arena-3d-apk`.

For a local build, open this folder in Android Studio or install Android SDK + Gradle 8.13, then run:

```bash
gradle --no-daemon :app:assembleDebug
```

APK output:

`app/build/outputs/apk/debug/app-debug.apk`

## Network requirement

The game is bundled in the app, but its Three.js ES modules are currently loaded from jsDelivr and its optional HDR environment texture is loaded from Poly Haven. An internet connection is therefore required for the 3D scene to initialize.

The app uses AndroidX WebKit's WebViewAssetLoader so bundled HTML is served from an HTTPS app-assets origin rather than a `file://` URL.

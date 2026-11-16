# GlassMusic Android project

A starter Android music player with a Liquid Glass-inspired Compose interface.

## Included
- Android 10+ target (minSdk 29)
- Local audio discovery through MediaStore
- Local playback using AndroidX Media3 ExoPlayer
- YouTube Music hand-off: opens the installed YouTube Music app, or music.youtube.com in a browser
- Search/filter for local tracks

## Important YouTube limitation
This app does not extract or stream YouTube audio. YouTube playback, ads, subscriptions and background-playback rules remain within the official YouTube/YouTube Music app or website. There is no unrestricted public YouTube Music playback API for third-party players.

## Build
Open this folder in Android Studio, allow Gradle sync, then Build > Build APK(s). The resulting debug APK is normally at `app/build/outputs/apk/debug/app-debug.apk`.

For a phone-only workflow, an Android IDE that supports modern Kotlin, Jetpack Compose, Android Gradle Plugin 8.7+, and SDK 35 may be used, but compatibility varies. This source ZIP is not itself an installable APK.

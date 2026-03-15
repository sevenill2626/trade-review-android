# Trade Review Android

This is a minimal Android wrapper that loads the deployed trade review site in a WebView.

## Prerequisites
- Android Studio (with Android SDK)
- JDK 17

## Open and run
1. Open Android Studio.
2. Select "Open" and choose this folder:
   `D:\Program Files (x86)\CodeX\trade-review-android`
3. Let Gradle sync finish.
4. Run on an emulator or a physical device.

## Change the website URL
Edit the URL in:
`app/src/main/java/com/tradereview/app/MainActivity.kt`

## Notes
- LocalStorage is supported in WebView, so your records stay on device.
- For multi-device sync, use the GitHub sync feature inside the web app.

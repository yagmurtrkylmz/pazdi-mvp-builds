# Pazdi MVP test builds

Installable Android builds of the Pazdi Wardrobe Tracker MVP. The source code lives in a private repository; this one carries only the files a tester needs.

## Install on an Android phone

1. Open the latest release under **Releases**, on the right of this page.
2. Under **Assets**, tap `Pazdi-MVP-android.apk` to download it.
3. Open the downloaded file and allow the install when Android asks about an unknown source.
4. Android 7.0 or newer is required.

## On an emulator

```
adb install -r Pazdi-MVP-android.apk
```

## Good to know

- The build is signed with a debug key, so it is for internal testing and cannot go to Google Play as it stands.
- The app does not update itself. A new build means a new download.
- Everything you add stays on the device, and uninstalling the app clears it.

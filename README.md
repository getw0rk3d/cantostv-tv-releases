# CantosTV for Android TV — Downloads

Native **Android TV / Google TV / Fire TV / Chromecast** build of CantosTV.
This is a separate app from the phone version, built for D-pad remotes.

## Download

➡️ **[CantosTV-AndroidTV.apk](CantosTV-AndroidTV.apk?raw=1)**

> Preview build (v0.1). Sideload it onto your TV device.

## Install on a TV device

**Easiest (Downloader app):**
1. Install the **Downloader** app from your TV's app store.
2. Open it and enter the direct APK link above.
3. Let it download, then choose **Install**.

**Via adb (advanced):**
```sh
adb connect <tv-ip>
adb install -r CantosTV-AndroidTV.apk
```

After installing, open **CantosTV** from your TV's apps row and sign in with your
playlist (Xtream host / username / password, or an M3U URL).

## Notes

- This is the TV-only app. The phone app is distributed separately.
- Your login is entered on the device; no credentials are bundled in the app.

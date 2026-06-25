# CantosTV for Android TV — Downloads

Native **Android TV / Google TV / Fire TV / Chromecast** build of CantosTV.
This is a separate app from the phone version, built for D-pad remotes.

## Download

➡️ **[Latest release (always newest version)](https://github.com/getw0rk3d/cantostv-tv-releases/releases/latest)**

Direct APK link (always points to the latest release — never goes stale):

```
https://github.com/getw0rk3d/cantostv-tv-releases/releases/latest/download/CantosTV-AndroidTV.apk
```

> Signed release. The version number lives on the [Releases page](https://github.com/getw0rk3d/cantostv-tv-releases/releases) so this README never has to be bumped per version.

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

Already installed? Update in-app via **Settings → Check for Updates**.

## Notes

- This is the TV-only app. The phone app is distributed separately.
- Your login is entered on the device; no credentials are bundled in the app.

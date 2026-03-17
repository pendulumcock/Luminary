# Luminary

Welcome to Luminary (Ampersand copy).

![Android Build Status](https://img.shields.io/github/actions/workflow/status/NyaomiDEV/Ampersand/build-android.yml?style=flat&label=android%20build)
![iOS Build Status](https://img.shields.io/github/actions/workflow/status/NyaomiDEV/Ampersand/build-ios.yml?style=flat&label=ios%20build)

[<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroidButtonGreyBorder_nofont.png" height="80" alt="Get it at IzzyOnDroid">](https://apt.izzysoft.de/packages/moe.ampersand.app)
[<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" height="80" alt="Get it on Obtainium">](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium://app/%7B%22id%22%3A%22moe.ampersand.app%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2FNyaomiDEV%2FAmpersand%22%2C%22author%22%3A%22NyaomiDEV%22%2C%22name%22%3A%22Ampersand%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22Release%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Atrue%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Atrue%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%5C%5C%5C((.*)%5C%5C%5C%5C)%24%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%241%5C%22%2C%5C%22versionDetection%5C%22%3Atrue%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22ampersand-.*%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22Ampersand%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22NyaomiDEV%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22Tracking%20app%20for%20plural%20systems%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Atrue%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%7D)
[<img src="https://raw.githubusercontent.com/xN1ckuz/xN1ckuz-Sidestore-Repo/main/Resources/Repo/sidestore_badge.png" height="80" alt="Add to AltStore">](altstore://source?url=https%3A%2F%2Fgithub.com%2FNyaomiDEV%2FAmpersand%2Freleases%2Flatest%2Fdownload%2Faltstore.json)


[Get the CI builds on Obtainium](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium://app/%7B%22id%22%3A%22moe.ampersand.app.ci%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2FNyaomiDEV%2FAmpersand%22%2C%22author%22%3A%22NyaomiDEV%22%2C%22name%22%3A%22Ampersand%20(CI)%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Atrue%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22CI%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22dontSortReleasesList%5C%22%3Afalse%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Atrue%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%5C%5C%5C((.*)%5C%5C%5C%5C)%24%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%241%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22ampersand-ci-.*%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Afalse%2C%5C%22appName%5C%22%3A%5C%22Ampersand%20(CI)%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22Tracking%20app%20for%20plural%20systems%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Atrue%2C%5C%22appAuthor%5C%22%3A%5C%22NyaomiDEV%5C%22%7D%22%7D)

## What is Ampersand?

Tracking web/app for friends :3

## Why would we need another app?

Because all other the other apps keep getting deleted 😭

## Can this be used yet?

No idk how to even see ts outside of code plus im just straightup tweaking ampersand

## What is ts compatible with?

The Android app is compatible with:
Android >= 8, provided Android System WebView is installed and used (check developer settings if unsure) and at least version >= 131

The PC version is compatible with:
- Linux computers (the majority of them, provided they're updated + you could compile Ampersand on one, it's easy!)
- Windows computers:
  - Running Windows 11
  - Snapdragon X laptops are not supported (check if yours is one [here](https://www.qualcomm.com/snapdragon/laptops-and-tablets/laptop-device-finder))
- Macs:
  - All Mac Studios
  - Mac Mini 2020 or later
  - Mac Pro 2023 or later
  - iMac 24" 2021 or later
  - MacBook Pro 14 inches, 2021 or later
  - MacBook Pro 16 inches, 2021 or later
  - MacBook Pro 13 inches, (M1) late 2020 or later
  - MacBook Air, (M1) late 2020 or later

## Where can I get Luminary?
Nowhere but you can get Ampersand:
We'd kindly advise you to install Ampersand outside of Google Play, given the nature of some legislations across the world that could take us the right to publishing there away.


Ampersand is available through Obtainium: https://apps.obtainium.imranr.dev/

For iOS users, Ampersand can be installed via AltStore or SideStore by adding the following source URL:
`https://github.com/NyaomiDEV/Ampersand/releases/latest/download/altstore.json`

Also you can download it through our GitHub mirror: https://github.com/NyaomiDEV/Ampersand/releases

Finally, and again please try to not be lazy about this, you can download it through Google Play Store: https://play.google.com/store/apps/details?id=moe.ampersand.app

## Can I contribute code?

Pls pls pls pls idfk what I'm doing pls

## Can I fund you?

No

## License

Please see the [License](LICENSE) file.

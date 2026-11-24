# Climper Store
### By Project Climper (CoolPyparusDude)
Climper Store is an open-source alternative to Indus Appstore. It is a rebrand/fork of Aurora Store, and we credit the Aurora OSS team for the original app, design, and features. Climper Store is independently maintained by Project Climper. 
#:D
<div class="example"><script src="https://keepandroidopen.org/banner.js"></script></div>

> Climper Store is an open-source rebrand/fork of Aurora Store, an alternative app store client for Google Play. It is based on the work of the Aurora OSS team. **All credit for Aurora Store’s original app, design, and features belongs to the Aurora OSS team.** Climper Store is independently maintained by Project Climper and is not affiliated with or endorsed by Aurora OSS, Google, Google Play, or Indus Appstore.

This README and rebrand was put together with help from Tencent Hy3.

Climper Store lets you search for and download apps from Google Play. You can view app descriptions, screenshots, updates, and reviews, and download APKs directly from Google Play to your device.

To use Climper Store, sign in with a Google Play account when you first open and configure the app.

Climper Store does not own, license, or host the apps it lists. App listings, descriptions, screenshots, and other content are accessed from Google Play.

**Disclaimer:** Climper Store is not approved, sponsored, or authorized by Google, Google Play, Indus Appstore, or the developers of apps available through it. It is not affiliated or partnered with any of them.

## Features

- Free and open source software, licensed under GPL-3.0.
- Material 3-based design.
- Sign in with a personal or anonymous account.
- Device and locale spoofing to access region-specific listings.
- Privacy information and tracker detection.
- App compatibility information for devices without Google Play Services or with microG.
- Update blacklisting to ignore updates for selected apps.
- Download manager.
- Manual downloads of older app versions, when the APK is available through Google Play and you know the version code.

## Limitations

- Climper Store relies on a reverse-engineered Google Play API. Changes to Google Play may cause features to stop working.
- Paid apps cannot be downloaded or updated.
- Apps and games using Play Asset Delivery cannot be updated.
- Some features are unavailable when using an anonymous account, including:
  - Library
  - Purchase history
  - Editor’s Choice
  - Beta programs
  - Writing or updating reviews
- The token dispenser server may experience downtime.

## AI Usage

Climper Store is developed with the help of AI tools.

**In this project**

- AI assistance may be used for coding, refactoring, reviewing changes, and drafting documentation.
- Maintainers review, understand, and test changes before merging them. Generated code is a starting point, not a finished result.
- Maintainers remain responsible for everything shipped in Climper Store.

**In contributions**

- Contributors may use AI tools. Please disclose their use in the merge request description.
- Contributors are responsible for their submissions and should be able to explain, build, and test their changes.
- Reports or contributions that appear to be unreviewed AI output, such as invented APIs or fabricated bug reports, may be closed without review.

## Downloads

Get stable releases from the [Project Climper releases page](https://github.com/CoolPyparusDude/ProjectClimper/releases).

## Support

Climper Store is under active development, so bugs are expected. Bug reports are appreciated.

## Permissions

- `android.permission.INTERNET` — connect to Google Play servers to download apps and updates.
- `android.permission.ACCESS_NETWORK_STATE` — check network availability.
- `android.permission.FOREGROUND_SERVICE` and `android.permission.FOREGROUND_SERVICE_DATA_SYNC` — keep downloads running in the background.
- `android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` — help optional automatic updates run without interruption.
- `android.permission.MANAGE_EXTERNAL_STORAGE`, `android.permission.READ_EXTERNAL_STORAGE`, and `android.permission.WRITE_EXTERNAL_STORAGE` — access OBB files for app expansion data, where supported by the Android version.
- `android.permission.QUERY_ALL_PACKAGES` — check installed apps for updates.
- `android.permission.REQUEST_INSTALL_PACKAGES` — install or update downloaded apps.
- `android.permission.REQUEST_DELETE_PACKAGES` — request app uninstallation.
- `android.permission.ENFORCE_UPDATE_OWNERSHIP` and `android.permission.UPDATE_PACKAGES_WITHOUT_USER_ACTION` — support update flows where the Android version and system allow them.
- `android.permission.POST_NOTIFICATIONS` — show download, update, and error notifications (optional).
- `android.permission.USE_CREDENTIALS` — support signing in with a personal Google account through microG.

## Screenshots

<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-01.png" height="400" alt="Climper Store screenshot">
<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-03.png" height="400" alt="Climper Store screenshot">
<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-07.png" height="400" alt="Climper Store screenshot">
<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-08.png" height="400" alt="Climper Store screenshot">

## Donations

Climper Store is a side project. We are not accepting donations at this time. If that changes, this section will be updated.

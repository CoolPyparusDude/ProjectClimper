
<div class="example"><script src="https://keepandroidopen.org/banner.js"></script></div>
#Credits To Aurora Store
This Is An OSS alternative To Indus Appstore
# Climper Store
### By Project Climper (CoolPyparusDude)

*Climper Store is a rebrand/fork built and maintained by Project Climper. This README and rebrand was put together with help from Tencent Hy3.*

Climper Store enables you to search and download apps from the official Google Play store. You can check app descriptions, screenshots, updates, reviews, and download the APK directly from Google Play to your device.

To use Climper Store, log in using your Google Play account when you first open and configure the app.

Unlike a traditional app store, Climper Store does not own, license or distribute any apps. All apps, app descriptions, screenshots and other content are directly accessed, downloaded and/or displayed from Google Play.

Climper Store works exactly like a door or a browser, allowing you to log in to your Google Play account and find the apps from Google Play.

*_Please note that Climper Store does not have any approval, sponsorship or authorization from Google, Google Play, any apps downloaded through it, or any app developers; neither does it have any affiliation, cooperation or connection with them._*

## Features

- FOSS: Has GPLv3 licence
- Beautiful design: Built upon latest Material 3 guidelines
- Account login: You can login with either personal or an anonymous account
- Device & Locale spoofing: Change your device and/or locale to access geo locked apps
- Privacy integration: Instantly see trackers in app
- Compatibility integration: Instantly see app compatibility without Google Play Services or with microG
- Updates blacklisting: Ignore updates for specific apps
- Download manager
- Manual downloads: allows you to download older version of apps, provided
  - The APKs are available with Google
  - You know the version codes for older versions

## Limitations

- The underlying API used is reversed engineered from the Google Play Store, changes on side may break it.
- Provides only base minimum features
  - Can not download or update paid apps.
  - Can not update apps/games with Play Asset Delivery
- Multiple in-app features are not available if logged in as Anonymous.
  - Library
  - Purchase History
  - Editor's choice
  - Beta Programs
  - Review Add/Update
- Token dispenser server is not super reliable, downtimes are expected.

## AI Usage

Climper Store is developed with the help of AI tooling. Here is what that means.

**In this project**

- AI assistance is used in day to day development: writing and refactoring code, reviewing diffs, and drafting documentation.
- Nothing gets merged that a maintainer has not read, understood and tested. Generated code is a starting point, not a finished result.
- Accountability does not change. Whatever ships in Climper Store is the maintainers' responsibility, no matter how it was written.

**In contributions**

- You are welcome to use AI tooling on your contributions. Just mention it in the merge request description.
- You are still responsible for what you send. Be ready to explain how your change works, and to show that you built and tested it yourself.
- Merge requests and issue reports that are plainly unreviewed model output (calls to APIs that do not exist, unrelated changes, made up bug reports) will be closed without review.

## Downloads

Get the latest stable releases here:

**github.com/CoolPyparusDude/ProjectClimper/releases**

## Support

Climper Store is still in on-going development! Bugs are to be expected! Any bug reports are appreciated.

## Permissions

- `android.permission.INTERNET` to download and install/update apps from the Google Play servers
- `android.permission.ACCESS_NETWORK_STATE` to check internet availability
- `android.permission.FOREGROUND_SERVICE` to download apps without interruption
- `android.permission.FOREGROUND_SERVICE_DATA_SYNC` to download apps without interruption
- `android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` to auto-update apps without interruption (optional)
- `android.permission.MANAGE_EXTERNAL_STORAGE` to access the OBB directory to download APK expansion files for games or large apps
- `android.permission.READ_EXTERNAL_STORAGE` to access the OBB directory to download APK expansion files for games or large apps
- `android.permission.WRITE_EXTERNAL_STORAGE` to access the OBB directory to download APK expansion files for games or large apps
- `android.permission.QUERY_ALL_PACKAGES` to check updates for all installed apps
- `android.permission.REQUEST_INSTALL_PACKAGES` to install and update apps
- `android.permission.REQUEST_DELETE_PACKAGES` to uninstall apps
- `android.permission.ENFORCE_UPDATE_OWNERSHIP` to silently update apps
- `android.permission.UPDATE_PACKAGES_WITHOUT_USER_ACTION` to silently update apps
- `android.permission.POST_NOTIFICATIONS` to notify user about ongoing downloads, available updates, and errors (optional)
- `android.permission.USE_CREDENTIALS` to allow users to sign into their personal Google account via microG

## Screenshots

<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-01.png" height="400">
<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-03.png" height="400">
<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-07.png" height="400">
<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/screenshot-08.png" height="400">

## Donations

Climper Store is a side project — we don't need donations right now. If it grows popular enough to be hard to manage, we'll revisit that.


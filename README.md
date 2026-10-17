
# PixelKit

PixelKit is an Android app project by AppMasterM. This repository contains the project source archive and GitHub Actions workflows used to build Android APKs.

## Download PixelKit

- **Releases:** https://github.com/AppMasterM/Pixel-kit/releases
- **Build artifacts:** https://github.com/AppMasterM/Pixel-kit/actions

## Features of This Repository

- Android APK build workflows using GitHub Actions.
- Debug APK build artifacts.
- Signed release APK build workflow.
- Source archive: `pixelkit-fixed.zip`.

## Download and Install

1. Open the [Releases page](https://github.com/AppMasterM/Pixel-kit/releases).
2. Download the PixelKit APK attached to the release.
3. If you downloaded a ZIP containing the APK, extract it first.
4. Open the APK on your Android device and follow the installation prompts.

Only install APKs from sources you trust.

## Building a Signed APK

The signed-release workflow uses GitHub Actions repository secrets:

- `KEYSTORE_BASE64`
- `KEYSTORE_PASSWORD`
- `KEY_ALIAS`
- `KEY_PASSWORD`

These secrets must be configured before running the signed-release workflow.

**Security:** Never upload your signing keystore or passwords publicly. Keep a secure backup of your signing key for future app updates.

## License

The original project code is intended to use the MIT License. See the `LICENSE` file. Third-party libraries and assets may have their own license terms.

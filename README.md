# Valnivo for Android

The Android app, for installing **without Google Play**. Every version is under
[Releases](../../releases); the newest file is always at
<https://github.com/valnivo-labs/valnivo-android/releases/latest/download/valnivo.apk>.

This repository holds no code. Valnivo is not open source; only the packages are published here,
because Google Play can currently serve the app to invited testers only.

**You do not need any of this to use Valnivo.** The app runs in a browser at
<https://valnivo.eu> and installs from there as a web app, with the same features.

## Before you install an APK

- Android will ask permission to install from this source. That prompt is the operating system, not
  a fault.
- **It does not update itself.** A new version means downloading it again from here.
- It carries our own signing certificate rather than Google's, so Android treats it as a different
  app from the Play copy. The two cannot be installed over one another, and switching either way
  means uninstalling first — **which erases figures kept only on the device**, unless you are signed
  in and have an encrypted cloud copy.
- It serves no ads and holds no advertising identifier.

Every release states its version, size and SHA-256, so you can check what you downloaded:
`shasum -a 256 valnivo.apk`.

## Something wrong?

Bugs and ideas go to [the feedback repository](https://github.com/valnivo-labs/valnivo-feedback/issues),
not here. Issues are disabled on this one.

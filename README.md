# Kiln

A native Windows file converter. Drop a file, hold a key, pick a format.

**[Download the latest release](https://github.com/chancrisp/kiln-releases/releases/latest)**

Kiln runs on 64-bit Windows 10 and 11.

## Which file to download

Each release has three files:

- **`Kiln-<version>-x64.msi`, the installer.** It installs into Program Files, adds a Start menu entry and puts `kiln` on PATH. It also adds Kiln to Open with for the files it converts and, for the account that installs it, to Send to.
- **`Kiln-<version>-x64-portable.zip`.** Unzip it anywhere and run `kiln-app.exe`.
- **`Kiln-<version>-third-party-source.zip`.** This is the source of the third-party code Kiln changed or builds itself. It contains the Symphonia files Kiln changed (MPL-2.0) and the build files for `lame_enc.dll`, the LAME MP3 encoder (LGPL). You don't need it to use Kiln.

## Updates

**Check for updates** in Kiln's Settings looks here for the latest release.

## Reporting problems

Bug reports and format requests are welcome in [Issues](https://github.com/chancrisp/kiln-releases/issues). Say which version of Kiln and Windows you have, what you converted, from which format to which, and what happened.

## License

Kiln is proprietary software, made by Chandler Crisp. All rights reserved. You may install and use the official builds published here. The third-party components it includes keep their own licenses. They are listed in `THIRD_PARTY_LICENSES` and `THIRD_PARTY_NOTICES.md`, which ship inside every download.

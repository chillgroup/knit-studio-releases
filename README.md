# KnitStudio releases

Installers of **KnitStudio**, the flat-knitting design editor (KnitPaint style). This repository holds the published
versions only; the source is elsewhere.

## Download

Open [Releases](../../releases/latest) and download the file for your computer:

| Computer | File |
| --- | --- |
| Windows (64-bit) | `KnitStudio-Setup-<version>.exe` |

Run the installer. Windows may show "Windows protected your PC" because the app is not code-signed: click
**More info ▸ Run anyway**.

## Updates

Once installed, KnitStudio looks for a new version by itself a few seconds after it starts, and from
**Help ▸ Check for updates…**. It asks before downloading; when the download is done choose **Restart now** (you are
asked to save your work first) or **Later** (it is installed when you close KnitStudio). Your settings and files are
kept.

Computers with KnitStudio 0.5.0 or older install a newer version by hand once; after that it updates itself.

## For the team

Releases are made by the `release-windows` workflow of the source repository when a tag `v<version>` is pushed. The
files of each release (`KnitStudio-Setup-<version>.exe`, its `.blockmap` and `latest.yml`) are what the app's updater
reads: do not rename or remove them.

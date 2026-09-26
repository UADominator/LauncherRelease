# KihaWorld Launcher — releases

Release feed for the KihaWorld Launcher. Nothing is built here: the GitLab
pipeline of the launcher repository publishes a release per tag with

* `KihaWorldLauncher_<version>_x64-setup.exe` — the Windows installer
* `KihaWorldLauncher_<version>_x64-setup.exe.sig` — its updater signature
* `latest.json` — what installed launchers poll to learn about this release
* the Linux `.deb` and AppImage

The launcher reads `https://github.com/UADominator/LauncherRelease/releases/latest/download/latest.json`.

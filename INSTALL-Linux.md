# Installing OpenAnalyst-beta on Linux

For Ubuntu 20.04, Debian 10, RHEL 8 or later (glibc 2.28), on X11 or Wayland: `linux-x64` for Intel and AMD,
`linux-arm64` for 64-bit ARM.

1. Download `OpenAnalyst-beta-<version>-linux-x64.zip` (or `-arm64`) and extract it into a folder of your own:
   `unzip OpenAnalyst-beta-*-linux-x64.zip -d ~/Apps`
2. Run `OpenAnalyst-beta` in it. If it isn't executable: `chmod +x OpenAnalyst-beta`.

It needs a Vulkan driver (`mesa-vulkan-drivers` on Debian, Ubuntu and Fedora, or the graphics
card's own) and, for file dialogs, a desktop portal (GNOME and KDE have one).

**To update**: the app looks for a newer version when it starts and downloads it; choose **Restart to update**. (Settings ›
Interface › Look for updates at start turns that off; Help › Check for updates… asks at once.) If it can't replace itself
it links to the download: close it and replace the folder. Settings and projects stay.

**To uninstall**, delete the folder.

This is a beta: keep copies of projects you can't make again. Maps, imagery and terrain come from the internet only when
you ask for them, and their provider is sent the area asked for. Looking for updates sends GitHub the app's version. There is
no telemetry.

By installing or using the app you agree to `LICENCE.txt`. The licences of the open-source parts are in
`THIRD-PARTY-NOTICES.txt`.

# Installing OpenAnalyst-beta on Windows

For Windows 10 or later: `windows-x64` for Intel and AMD, `windows-arm64` for ARM (Snapdragon).

1. Download `OpenAnalyst-beta-<version>-windows-x64.zip` (or `-arm64`), right-click it and choose **Extract All…**.
2. Move the folder somewhere of your own, such as `C:\Users\<you>\Apps`. (In `Program Files` the app can't update itself.)
3. Open `OpenAnalyst-beta.exe`. Windows may say it protected your PC, because the app isn't signed with a certificate:
   choose **More info**, then **Run anyway**. On a PC managed by an employer this may be turned off; ask them.

It needs a graphics driver with Vulkan or DirectX 12 (a virtual machine or a remote desktop may have neither). With DirectX 12
alone the first start can take some seconds longer.

**To update**: the app looks for a newer version when it starts and downloads it; choose **Restart to update**. (Settings ›
Interface › Look for updates at start turns that off; Help › Check for updates… asks at once.) If it can't replace itself
it links to the download: close it and replace the folder. Settings and projects stay.

**To uninstall**, delete the folder.

This is a beta: keep copies of projects you can't make again. Maps, imagery and terrain come from the internet only when
you ask for them, and their provider is sent the area asked for. Looking for updates sends GitHub the app's version. There is
no telemetry.

By installing or using the app you agree to `LICENCE.txt`. The licences of the open-source parts are in
`THIRD-PARTY-NOTICES.txt`.

# Revive Compatibility Layer

This is a compatibility layer between the Oculus SDK and OpenVR/OpenXR. It allows you to play Oculus-exclusive games on your HTC Vive or Valve Index.

[Refer to the wiki](https://github.com/LibreVR/Revive/wiki) if you run into any problems. You can also find a [community-compiled list of working games on the wiki](https://github.com/LibreVR/Revive/wiki/Compatibility-list), feel free to add your own results.

## Installation

*Always check the [compatibility list](https://github.com/LibreVR/Revive/wiki/Compatibility-list) before making a purchase.*

1. Download and install [Oculus Rift Software](https://www.oculus.com/rift/setup/). When you get to "Select Your Headset", choose to "Skip".
2. [Download the latest Revive installer.](https://github.com/LibreVR/Revive/releases/latest)
3. Install Revive in your preferred directory.
4. Start SteamVR if it's not already running.
5. Put on the headset, open the dashboard and click the new Revive tab.
6. If you run into any problems, read the known issues below or refer to the [wiki](https://github.com/LibreVR/Revive/wiki).

## Game-Specific Notes

### Stormland

For Stormland to work correctly with this version of Revive, the following files from the Revive installation **must be copied into the game's folder** (the same directory as `Stormland.exe`):

- `LibRevive64.dll`
- `openvr_api64.dll`

> **Note:** The standard Revive injection method (launching via the Revive Dashboard or right-click → Inject) does not work reliably with Stormland in our testing.

> **Important:** The game may fail to save progress if it is not started with **administrative privileges**.

## Known Issues

- Newly installed applications may refuse to start when you try to launch them for the first time, [simply follow these instructions to fix it](https://github.com/LibreVR/Revive/wiki/Troubleshooting#im-getting-an-entitlement-error-or-oculus-rift-not-found) or reboot your PC.
- If you don't see the Revive tab, go to the start menu on your desktop and start the Revive Dashboard. Or check the Applications tab in the SteamVR settings to see if the tab is enabled.

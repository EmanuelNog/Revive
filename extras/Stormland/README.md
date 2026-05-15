# Stormland Compatibility Files

These files are provided here for convenience to run Stormland with this version of Revive.

## Files

| File | Description |
|------|-------------|
| `LibRevive64.dll` | Revive runtime library (Oculus → OpenVR translation) |
| `openvr_api64.dll` | OpenVR API library |
| `xinput1_3.dll` | Controller input hook |
| `xinput9_1_0.dll` | Controller input hook (alternate) |
| `GammonConfig.ini` | Oculus identity spoofing configuration |

## Usage

Copy **all** files into your Stormland game folder (the same directory as `Stormland.exe`).

> **Note:** The standard Revive injection method (launching via the Revive Dashboard or right-click → Inject) does not work reliably with Stormland.

> **Important:** The game may fail to save progress if it is not started with **administrative privileges**.

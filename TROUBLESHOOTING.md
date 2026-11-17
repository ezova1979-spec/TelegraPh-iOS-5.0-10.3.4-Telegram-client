# Troubleshooting

**The app does not install**
Install AppSync Unified from Cydia, then try again. Make sure the file is not corrupted: the `.ipa` must be about 97 MB.

**The app crashes on launch**
Re-sign the executable with `ldid -S Payload/TelegraPh.app/Telegram` and reinstall. If it still crashes, attach the crash log to an issue.

**I have to log in again**
The bundle identifier changed to `dev.telegraph.client`, so old app data is not reused.

**Messages do not load / no connection**
Open Settings → Proxy and try a SOCKS5, WebSocket, VLESS or WARP profile. Check that the device date and time are correct; wrong time breaks TLS.

**The app is slow or closes in the background**
The iPhone 3GS has 256 MB of RAM. Close other apps, restart the device, and avoid very large chats and media.

**Where did the update check go?**
Automatic updates are disabled. Download new builds from Releases.

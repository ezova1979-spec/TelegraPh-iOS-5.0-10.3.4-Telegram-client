<p align="center">
  <img src="assets/icon.png" width="128" alt="TelegraPh icon">
</p>

<h1 align="center">TelegraPh</h1>

<p align="center">
  A Telegram client for old iPhones — built for <b>iOS 5.0+</b> (armv7), tested on iPhone 3GS.<br>
  <a href="README.ru.md">Русская версия</a>
</p>

---

## Features

- Runs on iOS 5.0 and newer, armv7 devices (iPhone 3GS and up)
- Chats, groups, channels, secret chats, voice messages, stickers, calls
- Proxy support (SOCKS5, WebSocket, VLESS subscriptions)
- Cloudflare WARP routing
- Classic iOS 6-style interface
- Languages: English, Русский, Deutsch, Español, Italiano, Nederlands, Português, 한국어, العربية

## Requirements

| | |
|---|---|
| Device | iPhone 3GS or newer (armv7) |
| iOS | 5.0 or newer |
| Jailbreak | **Required** (the app is not signed by Apple) |
| Installer | AppSync Unified (or equivalent) |

## Installation

1. Jailbreak your device and install **AppSync** from Cydia.
2. Download `TelegraPh-iOS5_0-armv7.ipa` from the [Releases](../../releases) page.
3. Install it with one of:
   - **iFile / Filza:** copy the `.ipa` to the device, open it, tap *Install*.
   - **iTunes / 3uTools / iFunBox:** drag the `.ipa` onto the device.
   - **SSH:** `ipainstaller TelegraPh-iOS5_0-armv7.ipa`
4. Respring. TelegraPh appears on the home screen.

If the app crashes on launch, re-sign it:

```sh
ldid -S Payload/TelegraPh.app/Telegram
```

## Notes

- The bundle identifier is `dev.telegraph.client`. It differs from earlier builds, so you need to log in again.
- The executable inside the bundle is still named `Telegram`; this is intentional.
- Auto-update is disabled.

## Credits & license

TelegraPh is a modified build based on open-source Telegram for iOS and its community forks.
Telegram for iOS is licensed under **GPL-2.0**, so this project and its source must stay under a compatible license and keep the original copyright notices.

This project is not affiliated with or endorsed by Telegram FZ-LLC.
"Telegram" is a trademark of its owner.

## Documentation

- [Troubleshooting](TROUBLESHOOTING.md)
- [Contributing](CONTRIBUTING.md)
- [Security policy](SECURITY.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Changelog](CHANGELOG.md)

## Contributing

Bug reports are welcome — please use the [issue templates](.github/ISSUE_TEMPLATE) and include your device model and iOS version.

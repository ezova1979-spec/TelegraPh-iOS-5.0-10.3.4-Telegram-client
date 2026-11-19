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
<h2>Cydia repository</h2>

<p>Add the repository to Cydia and install TelegraPh from there:</p>

<p align="center">
  <a href="https://ezova1979-spec.github.io/repo/">
    <img src="https://ezova1979-spec.github.io/repo/CydiaIcon.png" width="60" alt="TelegraPh repo">
  </a>
</p>

<ol>
  <li>Open <b>Cydia → Sources → Edit → Add</b></li>
  <li>Enter: <code>https://ezova1979-spec.github.io/repo/</code></li>
  <li>Open the source, choose <b>TelegraPh</b> and tap <b>Install</b></li>
</ol>

<p><b>Note:</b> old Cydia on iOS 5 may fail with an SSL error on HTTPS sources.
In that case download the <code>.deb</code> from
<a href="https://github.com/ezova1979-spec/repo/releases">Releases</a>
and install it with iFile or <code>dpkg -i</code>.</p>
<h2>or</h2>
1. Jailbreak your device and install **AppSync** and **AFC2** from Cydia.
2. Download `TelegraPh-iOS5-armv7.ipa` from the [Releases](../../releases) pagewith with
3. any installer on the PC.
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

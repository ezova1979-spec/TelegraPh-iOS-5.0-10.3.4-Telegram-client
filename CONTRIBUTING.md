# Contributing

Thanks for helping TelegraPh run better on old devices.

## Reporting bugs
- Search existing issues first.
- Use the **Bug report** template: device model, iOS version, jailbreak, installer.
- Attach a crash log from `/var/mobile/Library/Logs/CrashReporter` when the app crashes.

## Suggesting features
Open a **Feature request**. Keep in mind the target hardware: 256 MB of RAM on the iPhone 3GS, iOS 5.0, armv7 only. Heavy features may not be possible.

## Pull requests
1. Fork the repository and create a branch from `main`.
2. Keep changes small and focused: one fix or feature per PR.
3. Test on a real device or a simulator running iOS 5.x–6.x if possible, and say what you tested.
4. Update `CHANGELOG.md`.
5. Do not commit `.ipa` files or build output. Binaries go to Releases.

## Licensing
By contributing you agree that your contribution is released under the same license as the project. The project is based on GPL-2.0 code, so do not add code with an incompatible license.

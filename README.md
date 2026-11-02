# Extension Snapshot Toggle

A Chrome extension that saves which extensions are enabled, disables them all, and restores the saved state later. It's useful for checking whether another extension is causing a problem.

## Use

- **Save state + disable all:** saves which extensions are enabled, then disables them.
- **Restore all saved state:** re-enables the saved extensions and clears the snapshot.
- **Reset saved state:** clears the snapshot and leaves extensions as they are now.

While a snapshot is saved, the popup lists the extensions that were enabled. Tick one to re-enable it, or untick it to disable it.

## Install

1. Download the zip from the [latest release](https://github.com/jaymuchhala/extension-snapshot-toggle/releases/latest) and unzip it.
2. Open `chrome://extensions` and turn on Developer mode.
3. Click **Load unpacked** and choose the unzipped folder.

## Permissions

- `management`: to read, enable and disable your installed extensions.
- `storage`: to keep the snapshot in your browser. It's never sent anywhere.

## License

[MIT](LICENSE)

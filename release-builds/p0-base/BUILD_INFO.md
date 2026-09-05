# Handy Cloud P0 Base Build

- Source commit: `08cb0292dacc2ce4b8a1c64e8fff890e12cf72ec`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33937550651
- Target: `x86_64-pc-windows-msvc`
- Build signing: unsigned P0 fork build
- Updater artifacts: disabled for P0

## Installers
- `Handy Cloud_0.9.6_x64-setup.exe`
- `Handy Cloud_0.9.6_x64_en-US.msi`

## Automated P0 verification
- PASS — final tracked platform/tray icon assets differ byte-for-byte from cjpais/Handy and match the approved source marker.
- PASS — Windows x64 Tauri build completed and EXE/MSI artifacts were produced.
- PASS — NSIS installer icon and installed app icons were compared against the committed Handy Cloud icon.ico; MSI ProductName and app executable metadata were also checked.
- PASS — Win+H/blocking-hotkey source smoke guard and preserved core path checks completed without modifying core interaction logic.
- NOT INTERACTIVE-CI VERIFIED — physical global Win+H suppression, keydown/keyup delivery and end-to-end Push-To-Talk behavior require an interactive Windows desktop smoke test.

## SHA-256
85b7bbc4477f2ce40754b696614a6e682c5d9fe073a7b14de4f58ebd30a2913e  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
e066057f0349eeaf029e6beb17a9654bf6cfb38c403d03344eb1f99a09dbb643  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

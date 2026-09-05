# Handy Cloud P0 Base Build

- Source commit: `12e9850c4140620b233715c6cf8877764f664e24`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33945947531
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
7e7526bd232f49e85915121f5b5a9a5a9535f2ad1297a6f10efbb0cce4a34e5d  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
198514cdd60806a43a4e9d0a19222c48ed993fc56afa534bdb1d8ea461ac04c9  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

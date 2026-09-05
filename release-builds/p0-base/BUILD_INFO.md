# Handy Cloud P0 Base Build

- Source commit: `557aa8017e5b558bde14aa34a71889710bf6ac78`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33989636057
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
89224e56e195603ad9294116b0276a172d4d61b780d44c71093aee2a5bb6083f  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
a7f165b317af645ff7d6af3610b2231262e877e33f5e16f978d69095a6971068  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

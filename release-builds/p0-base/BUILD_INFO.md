# Handy Cloud P0 Base Build

- Source commit: `0e5052b852c350c0c02796c8870394168ad14022`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33953517332
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
425a3bf8802c3a4a69d902c627221218e3eca2562c7e7b01762cd4350bb786a3  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
4f8aa135b70e84d42ea0b953f64c526fd040663ee5c89276c5dd707cf5123508  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

# Handy Cloud P0 Base Build

- Source commit: `c797694af1cdec8fdd0b6cba6c62601de7db7277`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33951051880
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
8de991d9a9f6a5d7c287bcae01b2fcc3c44422f1bca77ca208cc233732621dd1  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
38ee806ecc4a173d92bbd78c497c20c2a165225b68c204ef3015cb9c8c52e07f  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

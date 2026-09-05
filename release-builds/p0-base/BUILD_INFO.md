# Handy Cloud P0 Base Build

- Source commit: `5ec0fdcd69fd3001d78ee781ebac92280d3c396a`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33987142910
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
1297d020eb8f44e95a22896f652e662763526a3e0c158921f91b2a470692bfa3  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
627e25e995b4cc3ae5c039ad6b28413f42a9ea405c4ce5ed6161585cdfcb5bfb  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

# Handy Cloud P0 Base Build

- Source commit: `eaae08bec1ba5c1e3f8cb6afea34c1b7a0e756c7`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33942470958
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
b00577a5ae25ff4374905fc16a05cd0c0722c0fd0a56bdac6bae11468843bddb  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
1240b32ec4bdf5827b5a05c5036d59d36be0c22ca0aa7fe65ee652b4a4ebcf21  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

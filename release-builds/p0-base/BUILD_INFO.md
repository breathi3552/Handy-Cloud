# Handy Cloud P0 Base Build

- Source commit: `8cf8652b9df2288e1330d9fe5cf2abb2b0df1936`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33658299492
- Target: `x86_64-pc-windows-msvc`
- Build signing: unsigned P0 fork build
- Updater artifacts: disabled for P0

## Installers
- `Handy Cloud_0.9.6_x64-setup.exe`
- `Handy Cloud_0.9.6_x64_en-US.msi`

## Automated P0 verification
- PASS — final tracked platform/tray icon assets differ byte-for-byte from cjpais/Handy and match the approved source marker.
- PASS — Windows x64 Tauri build completed and EXE/MSI artifacts were produced.
- PASS — MSI ProductName and NSIS executable version metadata were checked for Handy Cloud branding.
- PASS — Win+H/blocking-hotkey source smoke guard and preserved core path checks completed without modifying core interaction logic.
- NOT INTERACTIVE-CI VERIFIED — physical global Win+H suppression, keydown/keyup delivery and end-to-end Push-To-Talk behavior require an interactive Windows desktop smoke test.

## SHA-256
c44f99c841b378731d10ed4be5295dff5d8452498bf3c0ced16a8b8d00aaaada  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
230c0b132344575382759287314b1c141d015cb2f5ed17c9cb0d76c6004155e8  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

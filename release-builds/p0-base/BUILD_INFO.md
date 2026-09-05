# Handy Cloud P0 Base Build

- Source commit: `6dbcce05201288ceb0bf1fd984609474cd78acc1`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33968187314
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
e29799887725bff2baaeec52e3347b2deba3ac98c6a200e76989d11ec546ef08  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
f0bb4e2796a3e74afac620b7045b3b035da8e99659230280a94d352a11be15d4  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

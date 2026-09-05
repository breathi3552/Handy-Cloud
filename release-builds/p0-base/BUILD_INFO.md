# Handy Cloud P0 Base Build

- Source commit: `d851c83998d49f6482b565c74db7abc026918149`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33975024452
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
cac25fd3b5f09adce3eb7c10218a7cb85f76bb1dc3ec016232bf2430b82e2471  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
66a691cc2dc48632ab65ae4ee1de172e07a5953608b30ff2476ae1b3d325e96e  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

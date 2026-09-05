# Handy Cloud P0 Base Build

- Source commit: `1fb5d97e415fd80f2772d8a906268db0ad36825f`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33973337361
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
839bf5535f8341d84efa16b635b94a7ae135da36dfac1d2daf5bd9bb8b55e46d  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
dafb63234b54d3b09790a2b78efa0943241fbfcc438d60918c38c86fb1bc5eaf  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

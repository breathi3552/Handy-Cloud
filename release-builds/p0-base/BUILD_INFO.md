# Handy Cloud P0 Base Build

- Source commit: `3c200c17d23d2636cd75fd1fd4d52a8ecfa367eb`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33969862670
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
1a33bb9e82bb743fdb0e298375d388d6dab319e537cea59b5fc5d8e8622c93f1  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
7e72f3a679d51dcf43fb544063663091706679387d6d041293f1d320355b7862  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

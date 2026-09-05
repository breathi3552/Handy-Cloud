# Handy Cloud P0 Base Build

- Source commit: `ba683ad2eb19951c6eed61c702a9820767318814`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33940444765
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
be661ef5ad8257dbc75bf9b8da9d164d43eb1e45bac74c14334cb4ba3c51a49d  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
f09140081d073433231b02ea1898e4a7d7e7f9556bec8929f1b90d4782246095  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

# Handy Cloud P0 Base Build

- Source commit: `da9918593a83f6e564766ee952121a360c4bc3e5`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33948171000
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
a7293730e393015534396d3258c75d18b498f13ba5dfcdbb8a4155737057fb0b  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
a49a51891be05ba2f0e4ce664af7452499d7de268b6d082b756db7bf480d27ba  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

# Handy Cloud P0 Base Build

- Source commit: `58b3111c0f0b72fa13ae672b38b457ba85fd14ee`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33978125780
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
54c4f6d5f5fe712899277f359e8e8a45912bb7bb055e9c96e96958aa5d97e110  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
7f0064980ad6b1e5f39825304768b9c4ee87d17e77171d1fcebc81e7c7850d4e  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

# Handy Cloud P0 Base Build

- Source commit: `5b78c727c05ce3187cfaf6b097a0681e7d5b2b02`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33662885134
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
688794321aacc29d6c5178afb2021707df074a9d2c6fe32185c7d5ed4da1f1de  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
e90e4fe3732fc016be61c97d3367284e5549883bbc4dc04575213266b12c8ad4  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

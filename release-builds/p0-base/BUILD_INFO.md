# Handy Cloud P0 Base Build

- Source commit: `e3eac398b56c8f65ad9d26d8762009cab493d37b`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33971109625
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
cb06cadc8e4342fb7db730d3f1e72a929f677d9e22d6cc78a77d2dc2d473361a  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
4bcd26b3c83127370ac50b418b00dc079be490236dcd619ad0dcec9cb9b03e46  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

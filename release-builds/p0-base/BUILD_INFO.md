# Handy Cloud P0 Base Build

- Source commit: `06fdb6b872c3f6554429080e4273d97da669145f`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33492435602
- Target: `x86_64-pc-windows-msvc`
- Build signing: unsigned P0 fork build
- Updater artifacts: disabled for P0

## Installers
- `Handy Cloud_0.9.6_x64-setup.exe`
- `Handy Cloud_0.9.6_x64_en-US.msi`

## Automated P0 verification

- PASS — Windows x64 Tauri build completed.
- PASS — upstream Windows NSIS/MSI package runtime audit completed, including packaged executable launch via `--list-devices`.
- PASS — `handy-keys 0.3.4` remained in the Windows build dependency chain and the existing shortcut/text-injection source paths remain present.
- NOT INTERACTIVE-CI VERIFIED — physical global Win+H suppression, keydown/keyup delivery and end-to-end Push-To-Talk behavior require an interactive Windows desktop smoke test; GitHub-hosted runners cannot truthfully certify that shell-level behavior.

## SHA-256
eb76e36f1d8d013727a8e601758e6ee404d82e201e8d80a8b7a00d92a0e76679  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
12ed315ebe0053cedafb626a6707c58dcc2707deb73308041fc3d5e40e81e48a  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

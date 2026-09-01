# Handy Cloud P0 Base Build

- Source commit: `a7fc08c788d558f0ef93facdddacb57974ede2b5`
- CI run: https://github.com/breathi3552/Handy-Cloud/actions/runs/33498251965
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
ffb6bc7e0019bb3ae3f77e865ca419cc98d2498a9841f180c60e5316c1e950a4  release-builds/p0-base/Handy Cloud_0.9.6_x64-setup.exe
1ab6a669101c5c21cc1a1b7955529a72473d74eba1803055e1e704aa145e612e  release-builds/p0-base/Handy Cloud_0.9.6_x64_en-US.msi

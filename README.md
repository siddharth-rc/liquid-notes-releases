# Liquid Notes for Windows

Installers for **Liquid Notes**, the note-taking app by soEpic Technologies.

## Download

Get the latest installer from the [Releases page](../../releases/latest). Each release has:

- `Liquid-Notes-<version>.msi`: the Windows installer
- `SHA256SUMS.txt`: the SHA-256 checksum, to confirm the download is intact

To check a download in PowerShell:

```powershell
Get-FileHash .\Liquid-Notes-<version>.msi -Algorithm SHA256
```

The result should match the line for that file in `SHA256SUMS.txt`.

Liquid Notes is also available on Android from Google Play.

This repository only hosts release files; it does not contain the app's source code.

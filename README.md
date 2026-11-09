# KeyAI

KeyAI types AI answers directly into whatever Windows app has keyboard focus. Type your question, press your trigger hotkey, and the answer is typed in place. There is no overlay and no copy and paste.

## Download

Get the latest installer from the [Releases](../../releases/latest) page.

Each release contains:

- `KeyAI-Setup-vX.Y.Z.exe` the Windows installer
- `KeyAI-Setup-vX.Y.Z.exe.sha256` the SHA-256 checksum of the installer

KeyAI checks this page for updates and verifies the checksum before it installs one.

### Verify the download (PowerShell)

```powershell
(Get-FileHash .\KeyAI-Setup-vX.Y.Z.exe -Algorithm SHA256).Hash.ToLower()
```

The result must match the value in the `.sha256` file.

## Requirements

- Windows 10 or 11, 64-bit
- The setup installs the Interception keyboard driver if it is missing; a restart may be required
- Python 3.10 or newer; the setup offers to install it if it is missing

## Plans

- **Free**: bring your own Google Gemini API key
- **Pro**: 50,000 tokens per day
- **Premium**: 150,000 tokens per day, longer prompts and replies, and conversations that continue across hotkey presses

Paid plans are bought as 30-day passes inside the app.

## Notes

This repository only hosts installers and release notes. Source code is not published here.

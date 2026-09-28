# Founder IDE — Windows releases

Founder IDE is a desktop workspace from [Doxxed Crypto](https://doxxedcrypto.digital/founder-ide) for founders who want to build with AI agents. It combines a code workspace, AI chat, and local helpers in one Windows app. After installing, you can pair it with your account on the website.

This repository contains **installers and release notes only**. It has no source code.

## Download

**[Download the latest Windows installer](https://github.com/danishhaiderau-maker/founder-ide-releases/releases/latest)**

| Version | File | SHA-256 |
|---------|------|---------|
| 1.0.127 | `Founder-IDE-Next-QA-Setup-1.0.127.exe` | `a3fe20341b61d3a5acb6e43f307b6db64eb5aa2ddd056b5d12e2d9f49ef55f3a` |

Every release also includes a `SHA256SUMS` file.

## Verify your download

In PowerShell:

```powershell
Get-FileHash .\Founder-IDE-Next-QA-Setup-1.0.127.exe -Algorithm SHA256
```

The hash must match the one listed above and in that release's `SHA256SUMS`. If it doesn't match, don't run the installer.

## Unsigned installer — Windows SmartScreen warning

The installer is **not code-signed** yet, so Windows SmartScreen may say "Windows protected your PC". To continue, verify the SHA-256 hash first, then click **More info → Run anyway**. Only do this for files downloaded from this repository's Releases page.

## Requirements

- Windows 10 or 11, 64-bit
- About 1.3 GB of free disk space for the installer, plus more for the installed app

## Support

Visit <https://doxxedcrypto.digital/founder-ide>.

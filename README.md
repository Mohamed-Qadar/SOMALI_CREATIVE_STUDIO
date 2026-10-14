# Somali Creative Studio

Offline design and video editing for Somali creators, with English/Somali interfaces, editable local projects and **150 editable graphic templates**.

**0.6.3 Beta · Windows testing pre-release · Unsigned · Commercial acceptance pending**

## Download for Windows

<p>
  <a href="https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.3-beta/SomaliCreativeStudio-Windows-Setup.exe"><img src="docs/images/download-windows-setup.svg" width="280" height="60" alt="Download Windows Setup 0.6.3 (.exe)"></a>
  <a href="https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.3-beta/SHA256SUMS.txt"><img src="docs/images/download-checksums.svg" width="230" height="60" alt="Download SHA-256 checksums for 0.6.3"></a>
</p>

Text links: **[Windows Setup 0.6.3 (.exe)](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.3-beta/SomaliCreativeStudio-Windows-Setup.exe)** · [SHA-256 checksums](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.3-beta/SHA256SUMS.txt) · [Release notes and test results](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/tag/v0.6.3-beta)

Use Setup for installation, Start Menu shortcuts, an optional desktop shortcut and an uninstaller. This update prepares company-issued, computer-bound offline licenses for the **USD 4 / 30-day** plan. Actual paid activation remains **NOT TESTED**; this is a testing release.

### Install or update

1. Download Setup and its checksum file. Back up projects and close the editor.
2. Compare the downloaded file's SHA-256 with `SHA256SUMS.txt`:

   ```powershell
   Get-FileHash -Algorithm SHA256 .\SomaliCreativeStudio-Windows-Setup.exe
   ```

3. Run Setup under your ordinary Windows account. It upgrades a verified existing installation in place. Customer projects, templates, settings and license records are preserved. Keep the complete installed application folder and its media components, assets, notices and required third-party source together.

Target: **Windows 10 version 2004/build 19041 or later, or Windows 11, x64**. The application works offline after download; no product account, cloud backend, AI API, telemetry, domain or hosting is required. Clean-machine compatibility remains pending, and Windows N may need Media Foundation capabilities for video export.

### Activate or renew offline

Open **Activation and renewal**, copy the computer code and send it to the company through your existing contact. After manually confirming payment, the company supplies a signed `.scslicense` file. Choose **Import license / renewal...** and select that file. The computer code alone is not a license.

The configured Professional plan is **USD 4 for 30 days on one computer**; renewal is manual, with no automatic charge or online payment service. Early renewal preserves unused days. The app contains the company's public verifier only. Private signing keys and the separate company License Manager are excluded. Earlier disposable TEST licenses cannot activate this version. **Actual paid activation, renewal, expiry and restart persistence are NOT TESTED.**

### Older Portable ZIP

<a href="https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SomaliCreativeStudio-Windows-Portable.zip"><img src="docs/images/download-windows-portable.svg" width="210" height="60" alt="Legacy 0.6.1 Portable ZIP — no new company license support"></a>

[Legacy Portable ZIP 0.6.1](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SomaliCreativeStudio-Windows-Portable.zip) · [Its separate 0.6.1 checksums](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SHA256SUMS.txt)

**No 0.6.3 Portable ZIP is available. The older 0.6.1 package does not accept the new company-issued commercial licenses. Use Setup 0.6.3 for the update.**

## Beta limitations — read before testing

- **Unsigned testing software:** no signing reputation or complete commercial V1 acceptance is claimed. If machine policy refuses it, record the message without disabling protections.
- **Verified scope:** the exact 0.6.3 Setup passed an owned 0.6.2 → 0.6.3 upgrade on one Windows 11 development PC, preserving 735 existing sample files and 3 customer profile files. The installed executable passed native GPU and WARP startup checks. The production licensing build passed 50 customer unit tests and an actual executable graphic engine save/reopen/PNG roundtrip. These do not establish paid activation or human GUI acceptance.
- **NOT TESTED:** fresh clean Windows 10/11/N installation; this new installer's uninstall/reinstall lifecycle; real paid activation/renewal/expiry/restart; manual Open/Save/Save As/import/export dialogs, editing, playback and listening; Somali language review; beginner acceptance; representative 8 GB/integrated graphics machines. A separate fresh lifecycle attempt was BLOCKED by existing operator shortcuts and stopped before executing Setup.
- **Unresolved Windows video-template stall:** one earlier workflow exceeded its original 100-second bound. Later passes did not establish its cause.
- **Export destinations:** direct MP4 publication was qualified on local NTFS and needs hard-link support. Direct FAT/exFAT export is unsupported/unqualified; export to local NTFS and copy the completed file afterward.
- **Commercial review remains open:** codec/patent scope, copyright/brand ownership, company terms and multimedia redistribution obligations are not approved merely because an encoder or license verifier works. Retain bundled notices and required corresponding source.

This is a publicly downloadable pre-release for testing. Its testing purpose does not restrict who can download it. See the [full release notes](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/tag/v0.6.3-beta) for exact hashes, checks and limitations.

## Linux and macOS

**Linux remains on hold.** No Linux installer is published: intermittent Undo and physical desktop/dialog/playback acceptance remain unresolved or incomplete. WSLg engineering results do not qualify a physical Ubuntu desktop or other distributions.

No macOS download is available.

## Source and third-party notices

Proprietary application source, company licensing tools, customer records and private signing material are not published here. Required third-party notices/source accompany the Windows distribution independently of the private application source. GitHub's automatic source archives contain public documentation only; download the Setup asset for the updated application. The GPL-enabled development FFmpeg executable is excluded. Preserve bundled grants, source and recipient rights.

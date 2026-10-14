# Somali Creative Studio

Offline design and video editing for Somali creators, with English/Somali interfaces, editable local projects and 150 editable graphic templates.

**v0.6.1-beta · Windows x64 testing pre-release · Unsigned**

## Download for Windows

<p>
  <a href="https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SomaliCreativeStudio-Windows-Setup.exe"><img src="docs/images/download-windows-setup.svg" width="280" height="60" alt="Download Windows Setup (.exe) — recommended installer"></a>
  <a href="https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SomaliCreativeStudio-Windows-Portable.zip"><img src="docs/images/download-windows-portable.svg" width="210" height="60" alt="Download Windows Portable ZIP"></a>
  <a href="https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SHA256SUMS.txt"><img src="docs/images/download-checksums.svg" width="230" height="60" alt="Download SHA-256 checksums"></a>
</p>

Text links: **[Windows Setup (.exe)](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SomaliCreativeStudio-Windows-Setup.exe)** · [Portable ZIP](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SomaliCreativeStudio-Windows-Portable.zip) · [SHA-256 checksums](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/download/v0.6.1-beta/SHA256SUMS.txt)

Choose **Windows Setup** for normal installation, Start Menu shortcuts and an uninstaller. Choose **Portable ZIP** to extract and run the complete application folder.

[Read the full release notes and known issues](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/tag/v0.6.1-beta).

## Install and start

1. Download Setup or the Portable ZIP, plus `SHA256SUMS.txt`. Back up existing projects.
2. Check the downloaded file's SHA-256 against the checksum file. For example:
   ```powershell
   Get-FileHash -Algorithm SHA256 .\SomaliCreativeStudio-Windows-Setup.exe
   ```
3. Run Setup under your ordinary Windows account, or extract the complete Portable ZIP. Keep its media tools, assets, Samples, notices and required third-party source together. Do not move only the executable.

The target is **Windows 10 version 2004/build 19041 or later, or Windows 11, x64**. The application works offline after download; it needs no product account, cloud backend, AI API or telemetry service.

## Beta limitations — read before testing

- **Unsigned testing software:** no signing reputation or full commercial V1 acceptance is claimed. If machine security policy refuses it, record the message; do not disable protections.
- **Limited qualification:** installer, startup, engine editing/export, uninstall and reinstall checks passed on one Windows 11 development PC. Clean Windows 10/11/N, physical 8 GB/integrated graphics, human listening, Somali-language review and beginner acceptance remain unqualified. Windows N may lack the Media Foundation capabilities required for video export.
- **Unresolved Windows video-template stall:** one workflow exceeded its original 100-second bound. Later passes did not establish its cause.
- **Real file-dialog acceptance is incomplete:** the installed Open-project automation was blocked by a minimized-window guard. Manual picker/edit/export roundtrips are not claimed as passed.
- **Export destinations need care:** direct MP4 publication was tested on local NTFS and needs hard-link support. Direct FAT/exFAT export is unsupported/unqualified; export to local NTFS and copy the completed file afterward. Keep independent backups.
- **TEST licensing only:** included disposable TESTING licenses are for this pilot. Production licensing/signing keys are not provisioned, and the company License Manager is excluded.
- **Commercial review remains open:** codec/patent scope, company EULA, ownership/branding and commercial distribution rights are not approved merely because an encoder works. Keep all bundled notices and required corresponding source.

This is a publicly downloadable pre-release for testing. Its testing purpose does not restrict who can download it. See the [release notes](https://github.com/Mohamed-Qadar/SOMALI_CREATIVE_STUDIO/releases/tag/v0.6.1-beta) for exact artifact hashes, verified checks and remaining risks.

## Linux and macOS

**Linux remains on hold.** No Linux installer is published: the intermittent Undo timeout is unexplained and portal-dialog/pure installed playback acceptance is incomplete. WSLg engineering results do not qualify a physical Ubuntu desktop or other distributions.

No macOS download is available.

## Source and third-party notices

Proprietary application source, company licensing tools, customer records and private signing material are not published in this repository. Required third-party notices/source accompany the Windows distributions independently of the private application source. The GPL development FFmpeg executable is excluded. Preserve the bundled grants, source and recipient rights.


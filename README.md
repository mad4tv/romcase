<p align="center">
  <img src="Resources/AppIcon.png" width="128" alt="ROM Case">
</p>

<h1 align="center">ROM Case</h1>

<p align="center">
  <strong>English</strong> · <a href="README.pt.md">Português</a>
</p>

<p align="center">
  A native macOS case for retro handhelds — <strong>R36S</strong>, <strong>Anbernic</strong> (RG35XX and friends),<br>
  and the cards that hold their ROMs, BIOS, saves and covers.
</p>

<p align="center">
  <img src="Resources/os/logo-r36s.png" height="48" alt="R36S">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-anbernic.png" height="48" alt="Anbernic">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-arkos.png" height="48" alt="ArkOS">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-darkos.png" height="48" alt="dArkOS">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-amberelec.png" height="48" alt="AmberELEC">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-pan4elec.png" height="48" alt="PAN4ELEC">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-knulli.png" height="48" alt="KNULLI">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-rocknix.png" height="48" alt="ROCKNIX">
  &nbsp;&nbsp;
  <img src="Resources/os/logo-muos.png" height="48" alt="muOS">
</p>

<p align="center">
  <strong>ArkOS</strong> · <strong>dArkOS</strong> · <strong>PAN4ELEC</strong> · <strong>AmberELEC</strong> · <strong>KNULLI</strong> ·
  <strong>ROCKNIX</strong> · <strong>Anbernic Stock</strong> · <strong>muOS</strong>
</p>

<p align="center">
  <a href="https://github.com/mad4tv/romcase/releases/latest/download/ROM-Case-1.2.1.dmg">
    <img src="https://img.shields.io/badge/Download-ROM%20Case%201.2.1.dmg-4FB8FF?style=for-the-badge&logo=apple&logoColor=white" alt="Download ROM Case 1.2.1.dmg">
  </a>
  &nbsp;
  <a href="https://www.buymeacoffee.com/joseteixeira">
    <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-joseteixeira-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee">
  </a>
</p>

<p align="center">
  <a href="https://github.com/mad4tv/romcase/releases/latest"><strong>Download the installer (.dmg)</strong></a>
  ·
  v1.2.1 · macOS 14+ · Apple Silicon
  ·
  <a href="https://www.buymeacoffee.com/joseteixeira">Buy Me a Coffee</a>
</p>

---

## What it is

**ROM Case** is a Mac app for people who keep **R36S** clones and **Anbernic** handhelds (RG35XX Plus, H, Pro and the rest of that shelf) on more than one firmware.

It sees the SD card when you plug it in, names the OS (or lets you pick it), and then does the boring work that usually means a Finder window, the wrong folder, and a missing `.srm`.

English is the default language in the app when macOS is not Portuguese. Click 🇵🇹 or 🇬🇧 on the first-run menu (or in the sidebar) to switch; that choice is remembered.

The **source code stays private**. This page is the public documentation and the place to download the app.

## Download

**[ROM-Case-1.2.1.dmg](https://github.com/mad4tv/romcase/releases/latest/download/ROM-Case-1.2.1.dmg)** — drag **ROM Case** into Applications.

[All versions](https://github.com/mad4tv/romcase/releases)

### Requirements

- **macOS 14** (Sonoma) or later
- **Apple Silicon** (M1, M2, M3, M4)
- An SD card / USB card reader that the Finder can mount
- First launch: **right-click → Open** (the app is ad-hoc signed, so Gatekeeper asks once)
- Optional: a [ScreenScraper](https://www.screenscraper.fr) account if you want missing 2D box art filled in

No Xcode is needed to run the downloaded app.

## What the app does

| | Task | |
| :---: | --- | --- |
| <img src="Resources/menu/menu-prepare.png" width="72" alt="Prepare"> | **Prepare** | Write a handheld OS onto a blank SD (official image or a `.img` you already have). Typical devices: **R36S** (ArkOS, dArkOS, PAN4ELEC, AmberELEC, ROCKNIX, …) and **Anbernic** RG35XX (stock, KNULLI, muOS, ROCKNIX). Optional second card for ROMs only. **Erases the card.** |
| <img src="Resources/menu/menu-transfer.png" width="72" alt="Transfer games"> | **Transfer games** | Source (old SD, ROM folder, or mounted `.img`) → destination. Copies ROMs, BIOS, saves and covers into the folder each OS actually uses. |
| <img src="Resources/menu/menu-structure.png" width="72" alt="Folders"> | **Folders** | Create the empty OS layout on a new card before you copy anything. |
| <img src="Resources/menu/menu-covers.png" width="72" alt="Box art"> | **Box art** | Fill in missing 2D boxes via ScreenScraper (member account on screen). Then Update Gamelists on KNULLI / ArkOS. |
| <img src="Resources/menu/menu-themes.png" width="72" alt="Themes"> | **Themes** | Lists per OS (small 4:3 screens / Batocera / MustardOS) or drop a ZIP / `.muxthm` onto the card. The handheld still turns the theme on. |
| <img src="Resources/menu/menu-duplicates.png" width="72" alt="Duplicates"> | **Duplicates** | Find identical ROM files on the card and delete the extras. One copy is always kept. |
| <img src="Resources/menu/menu-backup.png" width="72" alt="Archive"> | **Archive** | Copy ROM folders to the Mac, or clone the **whole** SD to a `.img` (BOOT included) and restore it later. |

Also: the app **ejects** the whole physical card (not one partition) wherever a card or disk is shown, and it **refuses** to list or touch the internal Mac disk.

It will not mix layouts. ArkOS-style cards (R36S), Batocera/KNULLI, Anbernic stock and muOS stay in their own folders.

## Install

1. [Download `ROM-Case-1.2.1.dmg`](https://github.com/mad4tv/romcase/releases/latest/download/ROM-Case-1.2.1.dmg)
2. Open the disk image and drag **ROM Case** into **Applications**
3. First time: right-click the app → **Open** → confirm
4. Plug in an SD, or drop a folder / `.img`

If macOS says the app is from an unidentified developer, that is the ad-hoc signature. Right-click → Open is the intended path; do not disable Gatekeeper globally.

## Supported systems

| OS | Family | Handhelds (typical) |
| --- | --- | --- |
| ArkOS 2.0 | ArkOS | **R36S** · AeolusUX (archived) |
| dArkOS | ArkOS | **R36S** · dArkOSen |
| AmberELEC | ArkOS | RK3326 · RG351 · also **R36S** |
| PAN4ELEC | ArkOS | **R36S** Panel 4 |
| KNULLI | Batocera | **Anbernic** RG35XX |
| ROCKNIX | Batocera | **R36S** · RG35XX · JELOS |
| Anbernic Stock | Anbernic | **Anbernic** RG35XX Pro / Plus / H · original OS |
| muOS | MustardOS | **Anbernic** RG35XX · ARCHIVE for themes |

## Support the project

ROM Case is built by **José A. Teixeira** (AKA Mad4linux).

If it saved you an evening of copying the wrong folder:

**[Buy Me a Coffee](https://www.buymeacoffee.com/joseteixeira)**

## Credits

**ROM Case** — © 2026 José A. Teixeira · AKA Mad4linux

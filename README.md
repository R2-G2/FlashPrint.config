# FlashPrint.config: my 3D printing settings

## Preamble

### My workshop setup

#### Printer

- **Flashforge Adventurer 4** *[seamingly stock]*
    - w/ **Sunlu FilaDryer S2** *[simply enhanced]*
    - standalone
    - fed by **FlashPrint[.config](https://github.com/R2-G2/FlashPrint.config)**
- **Creality Ender-3Xs Pro** *[strongly upgraded, WIP]*
    - w/ **Sunlu FilaDryer S1** *[stock]*
    - klipperified
    - fed by **PrusaSlicer[.config](https://github.com/R2-G2/PrusaSlicer.config)**
- **Artillery Sidewinder X2** *[slighty modded, WIP]*
    - w/ **Sunlu FilaDryer S1** *[stock]*
    - klipperified
    - fed by **PrusaSlicer[.config](https://github.com/R2-G2/PrusaSlicer.config)**
- **Anycubic Photon Mono** *[simply enhanced]*
    - w/ **Anycubic Wash & Cure Machine 2.0** *[simply enhanced]*
    - standalone
    - fed by **PrusaSlicer[.config](https://github.com/R2-G2/PrusaSlicer.config)** &
        **[UVtools](https://github.com/sn4k3/UVtools)**

#### Klipper

- **Raspberry Pi 3 Model B+**
    - w/ **Raspberry Pi Touch Display**

### Find me on

- [Thingiverse](https://www.thingiverse.com/r2g2de)
- [3D-Druck-Community](https://www.3d-druck-community.de/member.php?action=profile&uid=16354)

## Structure

- **cfg/**: my configuration folder
    - **slice_profile/**: Slice Profile Settings
    - **slice_profile_def/**: Standard Slice Profile Settings

## Usage

### Universal

First of all, somehow transfer **FlashPrint.config** to your system (download ZIP, grab release, *clone* repository).

Then the easiest way is to copy the settings directories named under [Structure](#structure) to your **FlashPrint**
configuration folder.

If you (sym)link them, you will be able to keep a **Git** repository up to date without any hassle. Before that, make
sure to back up or copy your current settings to that repository.

### UN*X

Life is good if you are running a **UN\*X** (sub)system: just try out
**[FlashPrintConfig](https://github.com/R2-G2/FlashPrintConfig)**!

## Problems?

Fork! Fork it! Fork you! Fork me, right?

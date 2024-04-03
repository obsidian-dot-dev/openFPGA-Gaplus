# Gaplus

Gaplus-compatible hardware simulation for the Analogue Pocket.

* Based on the FPGA Gaplus implementation by [MiSTer-X](https://github.com/MrX-8B/MiSTer-Arcade-Gaplus)
* Ported from the [MiSTer](https://github.com/MiSTer-devel/Arcade-Gaplus_MiSTer) repo.

## Compatibility

This core supports both Galaga 3 and Gaplus romsets.  

## Usage

*No ROM files are included with this release.*  

Install the contents of the release to the root of the SD card.

Place the necessary `.rom` files for the supported games onto the SD card under `Assets/gaplus/common`.

To generate the `.rom` format binaries used by this core, you must use the MRA files included in this repo, along with the corresponding ROMs from the most recent MAME release.

## Known issues and limitations

* High-score saving is not supported.
* Dip-switches are not-yet supported.

## History

v0.9.0
* Initial Release.

## Attribution

```
---------------------------------------------------------------------------------
-- 
-- Arcade: Gaplus  port to MiSTer by MiSTer-X
-- 26 October 2019
-- From: https://github.com/MrX-8B/MiSTer-Arcade-Gaplus
-- 
---------------------------------------------------------------------------------
-- FPGA Gaplus for XILINX Spartan-3
--------------------------------------
-- Copyright (c) 2007 MiSTer-X
---------------------------------------------------------------------------------
-- Cycle-Accurate 6809 Core
-- Revision 1.0 - 13th August 2016
---------------------------------------------------
-- Copyright (c) 2016, Greg Miller
---------------------------------------------------------------------------------
```

See individual modules for more details.

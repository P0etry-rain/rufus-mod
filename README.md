# Rufus: The Reliable USB Formatting Utility



## PLEASE FOLLOW THE WARNING FROM TEAM RUFUS.
## DO NOT OPEN THIS TOOL IF YOU KNOW NOTHING ABOUT IT.
## I make some small modification to Rufus. To break limitation of flashing internal disk.
## This modified version is very dangerous. It can remove all the files from you disk. And they will never go back
## I need this tool to install openwrt_x86. So i make the modification. No offense.
## Make sure that all you step are safe if you insist use it.


_____________________________________
### `CtrlAlt-F` to switch cheat mode.
_____________________________________

[![VS2022 Build Status](https://img.shields.io/github/workflow/status/pbatard/rufus/VS2022.svg?style=flat-square&label=VS2022%20Build)](https://github.com/pbatard/rufus/actions/workflows/vs2022.yml)
[![MinGW Build Status](https://img.shields.io/github/workflow/status/pbatard/rufus/MinGW.svg?style=flat-square&label=MinGW%20Build)](https://github.com/pbatard/rufus/actions/workflows/mingw.yml)
[![Coverity Scan Status](https://img.shields.io/coverity/scan/2172.svg?style=flat-square&label=Coverity%20Analysis)](https://scan.coverity.com/projects/pbatard-rufus)  
[![Latest Release](https://img.shields.io/github/release-pre/pbatard/rufus.svg?style=flat-square&label=Latest%20Release)](https://github.com/pbatard/rufus/releases)
[![Licence](https://img.shields.io/badge/license-GPLv3-blue.svg?style=flat-square&label=License)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![Download Stats](https://img.shields.io/github/downloads/pbatard/rufus/total.svg?label=Downloads%20%28since%202019%29&style=flat-square)](https://github.com/pbatard/rufus/releases)
[![Contributors](https://img.shields.io/github/contributors/pbatard/rufus.svg?style=flat-square&label=Contributors)](https://github.com/pbatard/rufus/graphs/contributors)

![Rufus logo](https://raw.githubusercontent.com/pbatard/rufus/master/res/icons/rufus-128.png)

Rufus is a utility that helps format and create bootable USB flash drives.

Features
--------

* Format USB, flash card and virtual drives to FAT/FAT32/NTFS/UDF/exFAT/ReFS/ext2/ext3
* Create DOS bootable USB drives, using [FreeDOS](https://www.freedos.org) or MS-DOS (Windows 8.1 or earlier)
* Create BIOS or UEFI bootable drives, including [UEFI bootable NTFS](https://github.com/pbatard/uefi-ntfs)
* Create bootable drives from bootable ISOs (Windows, Linux, etc.)
* Create bootable drives from bootable disk images, including compressed ones
* Create Windows 11 installation drives for PCs that don't have TPM
* Create [Windows To Go](https://en.wikipedia.org/wiki/Windows_To_Go) drives
* Create persistent Linux partitions
* Create VHD/DD images of a drive
* Compute MD5, SHA-1, SHA-256 and SHA-512 checksums of the selected image
* Perform bad blocks checks, including detection of "fake" flash drives
* Download official Microsoft Windows 7, Windows 8, Windows 10 or Windows 11 retail ISOs
* Download [UEFI Shell](https://github.com/pbatard/UEFI-Shell) ISOs
* Modern and familiar UI, with [38 languages natively supported](https://github.com/pbatard/rufus/wiki/FAQ#What_languages_are_natively_supported_by_Rufus)
* Small footprint. No installation required.
* Portable. Secure Boot compatible.
* 100% [Free Software](https://www.gnu.org/philosophy/free-sw) ([GPL v3](https://www.gnu.org/licenses/gpl-3.0))

Compilation
-----------

Use either Visual Studio 2022 or MinGW and then invoke the `.sln` or `configure`/`make` respectively.

#### Visual Studio

Rufus is an OSI compliant Open Source project. You are entitled to
download and use the *freely available* [Visual Studio Community Edition](https://www.visualstudio.com/vs/community/)
to build, run or develop for Rufus. As per the Visual Studio Community Edition license,
this applies regardless of whether you are an individual or a corporate user.

Additional information
----------------------

Rufus provides extensive information about what it is doing, either through its
easily accessible log, or through the [Windows debug facility](https://docs.microsoft.com/en-us/sysinternals/downloads/debugview).

* [__Official Website__](https://rufus.ie)
* [FAQ](https://github.com/pbatard/rufus/wiki/FAQ)

Enhancements/Bugs
-----------------

Please use the [GitHub issue tracker](https://github.com/pbatard/rufus/issues)
for reporting problems or suggesting new features.

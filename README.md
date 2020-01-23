# AHKv2-Gdip
This repository contains the GDI+ library (Gdip_All.ahk) compatible with both AHK v1.1.32.00 and [AHK v2-a108](https://autohotkey.com/v2/)

Support for AHK v1.0 is dropped (find the original `Gdip_All.ahk` library if you need that).  

See the [commit history](https://github.com/mmikeww/AHKv2-Gdip/commits/master) to see the changes made.

# Examples
See the appropriate Examples folder for usage examples

# Usage
All of the Gdip_*() functions use the same syntax as before, so no changes should be required, with one exception:  

The `Gdip_BitmapFromBRA()` function requires you to read the .bra file witih `FileObj.RawRead()` instead of the `FileRead` command. See the Tutorial.11 file in the Examples folder

# History
- @tic created the original [Gdip.ahk](https://github.com/tariqporter/Gdip/) library
- @Rseding91 updated it to make it compatible with unicode and x64 AHK versions and renamed the file `Gdip_All.ahk`
- this repository updates @Rseding91's `Gdip_All.ahk` to fix bugs and make it compatible with AHK v2


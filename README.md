# ks225-custom-firmware
An effort to build a custom firmware for Kasa and Tapo light dimmers (e.g. KS225)

## Backups
Flashing backups with either `ltchiptool` *or* `AmebaZII_PGTool` results in errors. So does downloading a full flash image built with `libretiny`, so flashing part by part might work better - TBD.

## Flashing
The firmware can be built for `wbr3` (which I believe was able to flash over the default firmware).

To use `generic-rtl8720cf-2mb-992k`, the separate partitions (partition table, bootloader and only then system) have to be flashed one by one with `AmebaZII_PGTool`.

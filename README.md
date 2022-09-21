# Lenovo-M920s-N000-OC

## macOS version
10.15.7 (I will update soon!)

## OC version
0.6.5 (I will update soon!)

## PC Configuration
CPU: i7 8700

iGPU: UHD630

eGPU: None

Mother Board: Q470

RAM: Samsung 8G 2933MHz DDR4

Ethernet: Intel 1219

NVMe SSD: KXG6AZNV256G TOSHIBA

SATA HDD: ST1000DM003-1SB102

Wireless and Bluetooth: None

Audio: Do Not Know

## Known Issues
VGA no output

## What works
HDMI*2 dual display

Ethernet

All USB ports

Audio input and ouput

## Not test yet
HDMI audio output

PS/2 Port

## Note
Please gen your own SMBIOS before boot and install!!! Its blank now (And add -v in boot-args if you need)

Unlock CFG using efi

## BIOS config
Secure Boot -> Disable
Display output:IGD 64M Max
ATA: SATA AHCI
Intel Virtualization -> Enable   （VT-x）
VT-d -> Disable
Intel Manageability -> Disable
Intel SXG -> Disable
Intel SIPP -> Disable
CSM->Disable
Boot->UEFI


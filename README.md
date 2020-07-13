# ucam-firmware

This repo contains releases of Ucam firmware. Please check them out here. 

https://github.com/iotexproject/ucam-firmware/releases

In each release, `linux.bin` is for updating firmwware from SD card. `update.bin` is for updating firmware from OTA (you will get update notice directly from your app).

## Update from SD card

- Make sure SD card in FAT32 format (otherwise please re-format it to FAT32)
- Copy linux.bin to the root path in SD card
- insert SD card to Ucam
- reboot Ucam and wait for the update
- Take SD card out after update successfully.

# Retrowarez XU4

Odroid XU4 + Batocera Linux + Pre-loaded roms

This is an Ansible playbook which is run on localhost (i.e. a Linux laptop) after Batocera Linux is flashed onto a 64 GB SD card. It will copy the missing BIOS's and ROMs onto the SD card.

### Step by Step Instructions on Preparing the SD Card
1. Download the latest XU4 image from here [https://batocera-linux.xorhub.com/#download] and extract the .img
2. Use Etcher to flash it to a micro SD card using an SD card reader.
3. Boot up the Odroid XU4 with Batocera so it expands the filesystem.

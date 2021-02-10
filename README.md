# Armbian for Tanix TX6 tv box

This is a fork of armbian with added config files and patches for Tanix TX6 tv box (Allwinner H6). WiFi & BT support is not added.

## Compile
For compiling the image for Tanix TX6 follow the normal procedure of compiling an Armbian image. I have deleted and disabled most unneeded files from armbian repo thus this repo size is a lot smaller and also doesn't download any unnecessary toolchain. Created image doesn't need any modification, just write it to an SD card using Etcher.

## Info
Configs are not depending on any third party repo, mainline linux and mainline u-boot are used to make it easier to maintain. Most kernel and u-boot patches are from Libreelec project. 

Currently supported kernel : 5.10.x

Currently supported u-boot : v2021.01

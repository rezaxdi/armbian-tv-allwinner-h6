# Armbian for Tanix TX6 tv box

This is a fork of armbian with added config files and patches for Tanix TX6 tv box (Allwinner H6). WiFi & BT support is not added.

## Compile
For compiling the image for Tanix TX6 follow the normal procedure of compiling an Armbian image. In "Choose a board menu" select "Show CSC/WIP/EOS/TVB" from bottom of the page and then select Tanix TX6 from the menu. Only ubuntu focal is tested. Created image doesn't need any modification, just write it to an SD card using Etcher.

## Info
Configs are not depending on any third party repo, mainline linux and mainline u-boot are used to make it easier to maintain. Most kernel and u-boot patches are from Libreelec project. 

Currently supported kernel : 5.10.x

Currently supported u-boot : v2021.01

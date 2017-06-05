# nmOS

## Description

A customised GNU/Linux distribution by mpstmeglug.
Remixed from ubuntu and tailor made for educational purposes.

**Method of developing the distro**- Remix  
**Base**- Ubuntu server 16.04.2 LTS release  
**Desktop environment**- LxQt  
**Display server**- Wayland  
**File system**- ZFS vs ext4  
**Icon theme**- Numix  
**Bootmode**- systemd vs GRUB  
**Mirroring**-  
**Time server**-   

## Preparing the build environment

We are using a virualbox as vm as the development environment.
Find the associated appliance in the vm directory.

We recommend using the same configuration accross all dev hosts to avoid unnecessary conflicts during sync.
Hence it's advisabe if you just import the appliance and attach the necessary VDI and ISO images.

The installation uses ubuntu image `ubuntu-16.04.2-desktop-amd64.iso` with the sha1 hash `4375b73e3a1aa305a36320ffd7484682922262b3`

During install
 - Keep the default selection for everything
 - Do not install third party mpeg codecs
 - When prompted create the user, keep the username `builder`
 - 

<!-- ## Installation instructions
### Dependencies
### Method-1
### Method-2
### Including additional packages

## Latest release

## Documentation

## About Us
 -->

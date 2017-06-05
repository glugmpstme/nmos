# nmOS

## Description

A customised GNU/Linux distribution by mpstmeglug.
<<<<<<< HEAD
Remixed from Ubuntu and tailor made for educational purposes.

 - **Base:** Ubuntu Desktop 16.04.2 LTS
 - **Desktop environment:** LxQt
 - **Display server:** Wayland
 - **File system:** ZFS vs ext4
 - **Icon theme:** Numix
 - **Mirroring:**  
=======
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
>>>>>>> 5e6fdb701d27bf289472b1ff550e2ed892748fd4

## Preparing the build environment

We are using a virualbox as vm as the development environment.
Find the associated appliance in the vm directory.


 - We recommend using the same configuration accross all dev hosts to avoid unnecessary conflicts during sync.
Hence it's advisabe if you just import the appliance and attach the necessary VDI and ISO images.

Pre install:
 - Uses ubuntu image `ubuntu-16.04.2-desktop-amd64.iso` with the sha1 hash `4375b73e3a1aa305a36320ffd7484682922262b3`
 - Create a VDI with at least 25GB space
 - Keep the VM offline until after the install finishes

During install
 - Change the locale to Kolkata
 - Keep the default selection for everything else
 - Do not install third party MPEG codecs
 - When prompted to create the user, keep the username `builder`

<!-- ## Installation instructions
### Dependencies
### Method-1
### Method-2
### Including additional packages

## Latest release

## Documentation

## About Us
 -->

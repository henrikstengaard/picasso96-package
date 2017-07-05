# Picasso96 package

Picasso96 package contains all you need to get Picasso96 up and running on your Amiga.

Picasso96 offers support for many different Amiga graphics boards, has builtin HiColor and TrueColor support for intuition screens and much
more.

## Description

Picasso96 package is based on Picasso96.lha from http://aminet.net/driver/video/Picasso96.lha and updated rtg.library v40.3993 from http://guide.abime.net/wb3.1/files/Picasso96.lha created by Paul, The Green Amiga Alien.

It has been converted to a package for HstWB Installer and automatically installs Picasso96 as described in "Chapter 5 - How to Install Picasso96" here http://guide.abime.net/wb3.1/chap5.htm written by Paul, The Green Amiga Alien.

## Requirements

Picasso96 package has following requirements:

- Kickstart and Workbench 3.0 (V39) or later,
- Motorola MC68020 processor or better,
- Altais, CyberVision64, CyberVision64/3D, Domino, Merlin, oMniBus,
  PicassoII, PicassoII+, PicassoIV, Piccolo, Piccolo SD64, Pixel64,
  Retina BLT Z3, Spectrum or uaegfx (for UAE, the UNIX/unusable/usable
  Amiga Emulator).

## Installation

Download latest release from https://github.com/henrikstengaard/picasso96-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure Picasso96 package using defined assigns.

## Assigns

Installation of Picasso96 package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

Picasso96 files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.
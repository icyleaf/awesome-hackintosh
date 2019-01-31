# Awesome Hackintosh

A curated list of awesome articles, kexts, tools and shiny things for Hackintosh.

## Table of Contents
<!-- TOC -->

- [Table of Contents](#table-of-contents)
- [Glossary](#glossary)
- [Tools](#tools)
  - [Installer](#installer)
  - [Boot Launcher](#boot-launcher)
  - [Configuration](#configuration)
- [Kexts](#kexts)
- [EFIs](#efis)
- [Tutorial](#tutorial)
  - [Guide](#guide)
  - [Successed](#successed)
- [Community](#community)

<!-- /TOC -->

## Glossary

## Tools

### Installer

- UniBeast
  - [9.0.0 Mojave](https://www.tonymacx86.com/resources/unibeast-9-0-0-mojave.406/)
  - [8.3.2 High Sierra](https://www.tonymacx86.com/resources/unibeast-8-3-2-high-sierra.383/)
  - [7.1.1 Sierra](https://www.tonymacx86.com/resources/unibeast-7-1-1-sierra.333/)

### Boot Launcher

- Clover
  - [RehabMan's builder](https://bitbucket.org/RehabMan/clover/downloads/)
  - [Dids's builder](https://github.com/Dids/clover-builder/releases)

### Configuration

- [Clover Configuration](https://mackie100projects.altervista.org/download-clover-configurator/)

## Kexts

- Boot Launcher
  - FakeSMC - Mantatory kext that emulates a Mac and is required to boot a hackintosh. When you download FakeSMC the folder will also contain Sensor kexts that you can use to monitor your hackintosh read about that here : HWMonitor Sensor Guide
  - Lilu – Arbitrary kext that is required other kexts to work like AppleALC.kext & NvidiaGraphicsFixup.kext. Some Gigabyte motherboards have trouble with some versions of Lilu.kext breaking audio. I recommend those users use v1.0.0, instead of the latest version.
- USB
  - USBInjectAll – Injects all USB ports
  - XHCI-200-series-injector.kext – Enables USB 3 device detection and USB 3 speeds on Kaby Lake motherboards. This kext is also recommended to have during the macOS install process so you can use those USB 3 ports and flash drives.
- Graphics Card
  - WhateverGreen.kext – Enables AMD graphic cards in macOS 10.12.6 or later. Will require Lilu.kext. Read about it here : How to hackintosh AMD graphics cards in Sierra 10.12.6+
  - NvidiaGraphicsFixup.kext – Allows the latest Mac SMBIOS definitions to be used like iMac 17,x and iMac 18,x. You would want to use these SMBIOS defintions if you are using a Skylake or Kabylake CPU respectively. Updating to the latest version may fix black screen issues.
  - IntelGraphicsFixup.kext – Fixes display and graphical issues when using integrated graphics. I also recommend setting DVMT Pre-Allocated to 128M or higher in BIOS if using the Intel iGPU to enable high resolution displays.
- Audio
  - AppleALC.kext – Enables audio on a hackintosh. Read about how to enable audio here: Hackintosh Audio Guide.  Some gigabyte users have problems with AppleALC.kext not enabling audio. I recommend them using v1.1.0, instead of the latest version.
  - HDMIAudio.kext – May help enable HDMI audio on some graphic cards. Read about it here : Hackintosh HDMI Audio + DisplayPort GFX Card Sound Guide
  - CodecCommander.kext – Fixes a problem with dim sounding or lower volume audio after sleeping/botting the hackintosh by updating EAPD (External Amplifier) state on HDA.
- LAN
  - IntelMausiEthernet – Enables ethernet for motherboards using an Intel Ethernet Chipset.
  - RealtekRTL8111.kext – Enables ethernet for motherboards using a Realtek Ethernet Chipset
- Wireless
- Bluetooth

- FakeSMC (none of the underscore sensor plugins needed, app not needed, just the one kext)
- IntelMausiEthernet

- WhateverGreen
- USBInjectAll

## EFIs

## Tutorial

### Guide
  - [Hackintosh Vanilla Desktop Guide](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide)
  - [Hackintosh-Installer-University](https://github.com/huangyz0918/Hackintosh-Installer-University)

### Successed

## Community

  - [tonymacx86.com](https://www.tonymacx86.com/)

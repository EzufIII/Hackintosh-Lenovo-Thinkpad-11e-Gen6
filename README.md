# Hackintosh on Lenovo ThinkPad 11e

Welcome to the Hackintosh setup guide for the Lenovo ThinkPad 11e! This guide provides the necessary resources and tools to install macOS on the Lenovo ThinkPad 11e Gen 6 using OpenCore as the bootloader.

**Note**: This is **not** a step-by-step tutorial, but rather a compilation of relevant information to help you through the process.

## Project Overview

The goal of this project is to enable the installation and operation of macOS on the Lenovo ThinkPad 11e Gen 6. The ThinkPad 11e is a budget-friendly device, and while macOS isn't officially supported, it is possible to get macOS running on it with the right configuration and setup.

### What You'll Find Here:

- Resources and tools to help you successfully install macOS
- Configuration files for OpenCore bootloader
- Details about what works and what doesn't on this particular hardware

## Hardware Specifications

The Lenovo ThinkPad 11e Gen 6 features the following components:

- **Processor**: Intel Core m3-8100Y
- **Graphics**: Intel UHD Graphics 615
- **Memory**: 8GB RAM
- **Storage**: 128GB SSD
- **Network Card**: Intel (specific model may vary)

## Software Prerequisites

- **macOS Version**: macOS Sonoma & Ventura (Tested with macOS **Ventura & Sonoma**)
- **Bootloader**: OpenCore

**Note**: This setup has been tested and verified on macOS Ventura, and newer macOS versions may not be fully compatible without further updates to the configuration.

## What's Working (So Far)

- **iGPU Graphics Acceleration**
- **Wi-Fi & Bluetooth**
- **Handoff & Universal Clipboard**:

## What's Not Working (Work in Progress)

- **Touchscreen**: Not functional (still investigating potential drivers or patches)
- **AirDrop & Continuity Features**: Not functional (features like AirDrop and Universal Control are currently not working)

## Installation Notes

- This setup requires advanced knowledge of Hackintosh installation procedures, including BIOS settings adjustments, OpenCore configuration, and kext installations.
- Ensure you have a USB drive (16GB or more) for creating a bootable macOS installer.
- If you're new to Hackintoshing, I recommend researching the Hackintosh community for general setup tips and troubleshooting strategies.

## License

This project is open source, and you are free to use and modify the provided resources for personal use. However, keep in mind that Hackintosh configurations can be inherently unstable, so use at your own risk.

## Link

EFI (use the most recent one! : [EFI](https://drive.google.com/drive/folders/1JpxRh1pAzdzEUDgpzRnIozxWf86ppdEl?usp=sharing)

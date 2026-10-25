# Raphael Embedded Node PCB

Custom PCB for the embedded hardware node of Raphael, a local AI engineering copilot.

## Overview

The embedded node is designed to support audio acquisition, lightweight event detection, and communication with a host computer over USB.

## Hardware

- MCU: ESP32-S3-WROOM-1-N8R8
- USB: USB Type-C
- Voltage regulator: AP2112K-3.3
- USB ESD protection: USBLC6-2SC6
- Audio interface: External I2S microphone connector

## I2S Interface

| Signal | ESP32-S3 GPIO |
|---|---|
| BCLK | GPIO4 |
| WS / LRCLK | GPIO5 |
| SD | GPIO6 |
| Power | 3.3 V |
| Ground | GND |

## Repository Structure

- KiCad project, schematic, and PCB layout files: Native hardware design.
- docs/evidence/: Genuine screenshots and validation records.
- manufacturing/: Fabrication outputs when generated.

## Development Status

PCB design and layout are in progress.

Design-rule checks, electrical validation, and mechanical verification must be completed before declaring the board fabrication-ready.

## Tools

- KiCad
- Git
- GitHub

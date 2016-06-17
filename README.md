# Myriad-RF Hardware

This repository contains the [Myriad-RF](http://myriadrf.org/) reference hardware designs for Lime Microsystem's LMS6002D and LMS7002M transceivers, plus LMS8001 up/down converter, in PDF and [KiCad](http://www.kicad-pcb.org) formats, along with the associated firmware.

## Contents

The directory structure for the hardware designs is as follows:

      docs/                      - platform documentation

      <project>/hardware/<version>/
          BOM/                   - bill of materials spreadsheet
          Gerbers/               - Gerber CAM files
          KiCAD/                 - KiCAD schematic and layout files
          Manufacturing/         - Additional manufacturing information
          PDF/                   - Schematic and layout PDFs
          Reports/               - DRC, ERC and drill reports

### Documentation

* RFDIO Connector Specification

The Myriad-RF Radio Frequency Digital Input Output (RFDIO) connector specification defines the electrical and mechanical properties of a high speed card interface for Field Programmable Gate Array (FPGA) based carrier boards. This specification ensures interoperability between carrier (mother) boards and add-on (daughter) RF cards.

*Please note that this needs to be updated with details of the connector specification used by the micro series of boards.*

### Myriad-RF 1 module (myriadrf-1)

Hardware design files for the LMS6002-based Myriad-RF 1 RF module.

Note that there are two versions of the design: one with vias in pads, and another with them off.

### DE0-Nano Interface (de0nano-interface)

Hardware design files and firmware sources (FPGA HDL + Cypress FX2 code) for the DE0-Nano interface that is used with the original Myriad-RF 1 module.

### Zipper Interface (zipper)

This interface allows the Myriad-RF 1 to be used with FPGA development boards that have either a HSMC or FMC connector.

*Note that v1 of the hardware design was not made generally available.*

### uMyriadRF-6002 (umyriadrf-6002)

LMS6002 version of the micro form factor RF module.

### uMyriadRF-7002 (umyriadrf-7002)

LMS7002 version of the micro form factor RF module.

### MyriadRF-8001 (myriadrf-8001)

LMS8001 Companion.

## Licensing

### Hardware

The hardware designs are licensed under a Creative Commons Attribution 3.0 Unported licence.

*Note: The Myriad-RF 1 and DE0-Nano Interface hardware designs were initially published under the Creative Commons Attribution-ShareAlike 3.0 Unported licence. As of 30th September 2013 these have been re-licensed under the more permissive Creative Commons Attribution 3.0 Unported licence.*

### Firmware

For details of firmware licensing please see the associated COPYING file(s).

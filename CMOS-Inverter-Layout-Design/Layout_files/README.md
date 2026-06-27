# Layout Files

## Overview

This folder contains the physical layout files of the **CMOS Inverter** designed using the **Magic VLSI Layout Editor** with **SCMOS Technology**. The layout follows SCMOS lambda-based design rules and represents the physical implementation of the CMOS inverter.

## Files Included

| File | Description |
|------|-------------|
| `cmos.mag` | Magic VLSI layout file containing the complete physical layout of the CMOS inverter, including transistor placement, routing, and layer information. |
| `cmos.ext` | Extracted netlist file generated from the layout. It contains the connectivity and parasitic information required for layout verification and post-layout simulation. |

## Purpose

The layout files are used to:

- Design the CMOS inverter physically.
- Verify layout connectivity.
- Perform layout extraction.
- Support Design Rule Check (DRC) and Layout Versus Schematic (LVS) verification.
- Prepare the design for post-layout simulation and fabrication.

## Software Used

- Magic VLSI Layout Editor
- SCMOS Technology

## Outcome

The generated layout files represent the completed CMOS inverter layout and its extracted connectivity information, ensuring that the physical design follows SCMOS design rules and is suitable for verification and further VLSI design processes.


# FU3 Phase-Locked Loop 22FDX-EXT

PLL design repository for the FU3 MCU using the 22FDX-EXT PDK.

## Directory structure

```text
22fdx/
|-- bandgap/
|-- charge_pump/
|-- divider_external/
|-- divider_internal/
|-- ldo/
|-- level_shifter/
|-- lock_detector/
|-- loop_filter/
|-- pfd/
|-- top/
`-- vco/
```

Each PLL block is maintained directly under `22fdx/`. The `top/`
directory contains the integrated PLL design.

## Technology and design environment

This project targets the GlobalFoundries 22FDX-EXT PDK. Schematic
design, simulation, layout, and verification are performed using
Cadence design tools.

The 22FDX-EXT PDK is proprietary and must not be committed to this
repository. Each designer must configure the PDK and Cadence
environment locally according to the project setup instructions.

## Required code header

All contributors must include the standard FTEL signature header in
every source code file. Copy the template from
[FTEL_signature.md](FTEL_signature.md), then replace all placeholders
and the example description with the correct author, email, date, and
module information.

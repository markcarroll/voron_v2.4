# My Voron V2.4 Build Log

- [My Voron V2.4 Build Log](#my-voron-v24-build-log)
  - [Build](#build)
    - [BOM](#bom)
  - [Mods](#mods)
    - [Afterburner PCB](#afterburner-pcb)
    - [Display Mount for 5" LCD](#display-mount-for-5-lcd)
    - [Bed Wagos](#bed-wagos)
    - [Nevermore Micro](#nevermore-micro)

## Build

I am building a 300mm Voron 2.4.

Ordered parts from Amazon, [West3D](https://west3d.com), [DigMach](https://store.digmach.com), [KB-3D](https://kb-3d.com/store/), Fabreeko, [Printed Solid](https://www.printedsolid.com) and [Mandala Rose Works](https://mandalaroseworks.com).

### BOM

| Part                                                     | Source                                                                                                          |
| -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Fasteners**                                            |
| Stainless Steel Fastener Kit for Voron 2.4               | West3D / [Amazon](https://amzn.to/3rF9ZNY)                                                                      |
|                                                          |
| **Motion**                                               |
| Voron 2.4 Motor Kit by OMC / Stepperonline               | West3D / [Amazon](https://amzn.to/3GNrimA)                                                                      |
| POWGE & GATES VORON 2.4 Motion Set - Black or Silver     | West3D / [Amazon](https://amzn.to/3AjkxGt)                                                                      |
| MGN9H linear rail × 8 350mm                              | DigMach                                                                                                         |
|                                                          |
| **Electronics**                                          |
| Wiring Harness for Voron 2.4 / Trident                   | West3D                                                                                                          |
| 6ft 18 AWG Power Cord (C13) UL-Listed Cable              | West3D                                                                                                          |
| Fuse 8A 250V Holder Cartridge 5 X 20mm Glass × 2         | West3D                                                                                                          |
| TycoElectronics - 10EHG1-2 Filtered Power Inlet          | West3D                                                                                                          |
| Omron G3NA-210B 24V Solid State Relay (SSR)              | West3D                                                                                                          |
| Mean Well RS-25-5 25W Power Supply (PSU)                 | West3D                                                                                                          |
| Mean Well LRS-200-24 200W 24V 8.8A Power Supply (PSU)    | West3D                                                                                                          |
| Rocker Switch DPST 16A On-Off                            | West3D                                                                                                          |
| PL-08N2 Inductive Probe                                  | [Amazon](https://amzn.to/33HAmuG)                                                                               |
| GDSTIME DC 24V 60x60x20 Axial Fan GDA6020 × 3            | West3D                                                                                                          |
| Din Rails                                                | [Amazon](https://amzn.to/34YqmgX)                                                                               |
| Din Rail Bracket Solid State Relay (SSR)                 | [Amazon](https://amzn.to/34YqmgX)                                                                               |
| Omron Micro Switch (D2F-01L) × 3                         | West3D                                                                                                          |
| 125C Cutoff 15A Thermal Fuse                             | West3D                                                                                                          |
| 24V Heater Tube                                          | [Amazon](https://amzn.to/3tKC9da)                                                                               |
| BAT85 Diode _(\*Not needed with Octopus Pro_)            | West3D                                                                                                          |
| Molex Microfit 3.0 Connectors - various                  | KB-3D                                                                                                           |
| \*Voron Afterburner Toolhead PCB - V3.rabbit             | KB-3D                                                                                                           |
| \*Voron Hall Effect X/Y Endstop PCB Assembled            | West3D / [Amazon](https://amzn.to/3KsJFzp)                                                                      |
| \*Sexbolt Z-Endstop Fully Assembled - Hartk              | West3D                                                                                                          |
|                                                          |
| **Controller**                                           |
| BigTreeTech Octopus Pro v1.0                             | [Amazon](https://amzn.to/3qGwa79)                                                                               |
| BigTreeTech TMC2209 Stepper Drivers x 8                  | [Amazon](https://amzn.to/3tIuBrq)                                                                               |
| BigTreeTech Mini12864 LCD Graphic Smart Display          | [Amazon](https://amzn.to/3Aj7rck)                                                                               |
|                                                          |
| **Frame**                                                |
| Angle Corner Connector 90 degree × 4                     | West3D                                                                                                          |
|                                                          |
| **Misc**                                                 |
| Rubber Compressor Feet 48x18mm                           | [Amazon](https://amzn.to/3tM2wPS)                                                                               |
| Bowden Coupler for 4mm OD PTFE Tube                      | West3D                                                                                                          |
| Bowden / PTFE Tube 4mm OD 3mm ID                         | West3D                                                                                                          |
| \*Voron Logo Sticker Decal                               | West3D                                                                                                          |
| \*Nevermore Carbon filtration media bags                 | Fabreeko                                                                                                        |
|                                                          |
| **Cables**                                               |
| VORON 2.4 Cable Chains Set 300mm                         | [Amazon](https://amzn.to/3GNr2DW)                                                                               |
|                                                          |
| **Panels**                                               |
| Voron 2.4 Panel Kit 300mm Side, Front & Top Only         | DigMach                                                                                                         |
| Voron V2 Panel Set Made From Aluminum Composite Material | [Printed Solid](https://www.printedsolid.com/products/voron-v2-panel-set-made-from-aluminum-composite-material) |
|                                                          |
| **Build Plate**                                          |
| Voron 300 Ultraflat Bed                                  | [Mandala Rose Works](https://mandalaroseworks.com/products/voron-300-standard-bed)                              |
| Keenovo Silicone Heater 240x240 600W 120V                | [Amazon](https://amzn.to/3Im5xdV)                                                                               |
| Magnetic Flex Plate Double-Sided (Texture/Smooth)        | [Amazon](https://amzn.to/3rvEB4o)                                                                               |

\* Mod only

---

## Mods

### Afterburner PCB

I decided on Hartk1213's ["Voron Afterburner Toolhead Board v3.rabbit (also known as ERCF PCB board)"](https://github.com/VoronDesign/Voron-Hardware/tree/master/Afterburner_Toolhead_PCB) since one day I may add a ERCF Filament changer.

You will also need a new PCB cover from [here](https://github.com/VoronDesign/Voron-Hardware/tree/master/Afterburner_Toolhead_PCB/STLs/Clockwork/Covers)

Since the PCB has a temperature sensor built in, I ended up using [this cover with air vents](https://github.com/craxoor/VoronMods/blob/master/PCB%20Cover/STL/Afterburner-PCBCover-AirVents.stl)

Wiring Diagram [here](https://github.com/VoronDesign/Voron-Hardware/blob/master/Afterburner_Toolhead_PCB/Images/Rev3.2/wiringDiagram.png)

```txt
Pinout
24V  - HE0 +V
GND  - PSU -V (NOT MAINS GND)
PROBE/ABL  - Probe Signal Pin
HE0  - Hotend Heater -V
CT   - Chamber Thermistor Signal Pin (TH1)
PCF  - Part Cooling Fan -V
HEF  - Hotend Cooling Fan -V
AGND - Hotend Thermistor -V
TH0  - Hotend Thermistor Signal Pin (TH0)
XES  - X Endstop Signal Pin
S1A  - Red Stepper Wire
S2A  - Green Stepper Wire
S1B  - Blue Stepper Wire
S2B  - Black Stepper Wire
```

### Display Mount for 5" LCD

Mount:  
<https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/sttts/Waveshare-5.5-inch-HDMI-AMOLED/STLs/Voron-2.4-Mount-Generisch-v6.stl>

Frame:  
<https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/alanho/BTT_PITFT50_v2_Mount>

### Bed Wagos

<https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/deepfriedheroin/v2_bed_wagos>

![Bed Wagos](https://github.com/VoronDesign/VoronUsers/blob/ef37f8709a9fe568c8f1ffa073bdab2cae82b404/printer_mods/deepfriedheroin/v2_bed_wagos/images/cad_image.jpg?raw=true)

Use the bed Wago mount to make the bed wiring pluggable:
![Bed wiring](https://github.com/VoronDesign/VoronUsers/blob/ef37f8709a9fe568c8f1ffa073bdab2cae82b404/printer_mods/deepfriedheroin/v2_bed_wagos/images/confusing_wiring_diagram.png?raw=true)

### Nevermore Micro

Instead of the extractor filter and fan I am installing the [Nevermore Micro V5 Duo](https://github.com/nevermore3d/Nevermore_Micro) mod.

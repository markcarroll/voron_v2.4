# My Voron V2.4 Build Log

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

https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/deepfriedheroin/v2_bed_wagos

![Bed Wagos](https://github.com/VoronDesign/VoronUsers/blob/ef37f8709a9fe568c8f1ffa073bdab2cae82b404/printer_mods/deepfriedheroin/v2_bed_wagos/images/cad_image.jpg)

Use the bed Wago mount to make the bed wiring pluggable:
![Bed wiring](https://github.com/VoronDesign/VoronUsers/blob/ef37f8709a9fe568c8f1ffa073bdab2cae82b404/printer_mods/deepfriedheroin/v2_bed_wagos/images/confusing_wiring_diagram.png)

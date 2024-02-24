# CrownCooler
This mod is designed to adapt a fan mounted somewhere on the frame, through a CPAP tube and onto a "crown" shaped cooling duct. It has been designed for the Voron 2.4 and Voron Trident series of printers, mounting directly to the stealthburner X carriage.

This mod was developed to:
- be compatible with standard voron stealthburner carriage
- be compatible with all extruder combinations that are compatible with the stealthburner system, (CW1, CW2, Orbiter, LGX Lite, etc.)
- mount a Rapido HF/UHF hot end & Dragon SF/HF/UHF hot end 
- improve overall cooling performance by accomodating very large fans and intaking cool air from outside the heated enclosure
- provide uniform cooling from all directions
- be lightweight and easy to maintain
- work with klickyprobe & euclid probe.

The design of the crown duct creates a fluid vortex at the tip of the nozzle, resulting in high cooling performance. It was designed using commercial CFD software, and validated experimentally. There is a secondary air cooling route fed by the part cooling fan to prevent warping of the duct from hot end heat. 

<img height="500" src="https://github.com/sneakytreesnake/CrownCooler/assets/12782053/74c4a7ec-f316-4417-a0e7-7440b1d52c16">

**This mod is still a BETA. Expect issues - but let me know about them so I can fix them.**

## V2.5 Update (February 2024)
The flow path has been updated in the latest version. It provides approximately **twice the cooling performance compared to the previous version!** In my testing, I was able to print 80degree angles at 30% fan rate (WS7040) with an enclosure temperature of 70C, 0.6mm nozzle size and 0.3mm layer height.

<img height="200" src="https://github.com/sneakytreesnake/CrownCooler/assets/12782053/8cca6188-6ca9-4a53-a915-d4124c97ca41"> <img height="200" src="https://github.com/sneakytreesnake/CrownCooler/assets/12782053/549b24a2-ac11-48a9-91bf-e81809008d80"> <img height="200" src="https://github.com/sneakytreesnake/CrownCooler/assets/12782053/562da77c-ff3f-4976-85aa-9819bffe673f">


# Gallery

<img height="400" src="https://user-images.githubusercontent.com/12782053/236075661-5eef9876-432e-4b2d-9f55-3736e35f87c8.jpg"> <img height="400" src="https://user-images.githubusercontent.com/12782053/236075664-2ce9a560-bdc1-4e15-8e94-6d1b76e40ca8.jpg"> <img height="400" src="https://user-images.githubusercontent.com/12782053/236075660-1e88b1c0-aee8-4450-aa71-69d7574bdeb9.jpg">


## CFD results:
You can clearly see a vortex being formed around the ring. This creates a cycle of air that rapidly carries heat from the printed part, allowing printong of steep overhangs.

<img height="225" src="https://github.com/sneakytreesnake/CrownCooler/assets/12782053/173023b3-ced1-4b6f-bc01-e7dc6b1ef601"> <img height="225" src="https://github.com/sneakytreesnake/CrownCooler/assets/12782053/de835ec7-2a6e-41e7-95e0-ca142d315e8a">

# Part Cooling Fan Options

There are a number of part cooling fan options to choose from, depending on your intended use case.

### 4028 fan

<img width="250" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/224202478-e5becb0b-ecc1-4771-b074-3288d9c18826.png">


A "medium" performance option is to use a 4028 fan on the end of the CPAP tube. This solution is best suited for ABS and similiar materials that do not require high amounts of part cooling. I do not recommend this option for printing PLA at high speeds.
A 4028 to CPAP tube adapter part is included in the STL files folder.

Recommended 4028 fans include:
- Sanyo 9GAX0412P3S001
- Delta FFB0412UHN-SM36

### 7040 blower fan

<img width="300" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/224202438-7c1f9482-3080-46ef-9dcf-3d7adbacfff1.jpg">

A "high" performance is to use a 7040 blower fan on the end of the CPAP tube. This solution is best suited for printing PLA & PETG at low to very high speeds. It can print ABS, however it will likely be cooled more than required (due to the minimum fan speed of the blower) - and the ABS part strength will be decreased.

A 7040 blower fan mount can be found [here.](https://www.printables.com/model/324265-ws7040-centrifugal-blower-fan-mount)

I recommend the WS7040 along with the controller board. I purchased mine from [Trianglelab here.](https://www.aliexpress.com/item/1005003822117604.html)

# BOM
- Coming soon...
  
# Installation instructions 
- This mod uses the standard stealthburner X carriage parts. T
- This mod should work with all types of extruder mounting parts, including CW2 (however, I have not yet tested it). I use the orbiter V2 extruder mount found [here](https://github.com/sneakytreesnake/StealthOrbiter).
- Print the cooling duct with no supports, file in STL folder. Use standard Voron print setting (0.6mm nozzle is acceptable)
- Only euclid and klicky probes are compatible at the moment. Use the offset klicky mount for HF hot ends, use the tall offset clock mount for UHF hot ends.









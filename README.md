# CrownCooler
This mod is designed to adapt a fan mounted somewhere on the frame, through a CPAP tube and onto a "crown" shaped cooling duct. It has been designed for the Voron 2.4 and Voron Trident series of printers, mounting directly to the stealthburner X carriage.

This mod was developed to:
- be compatible with standard voron stealthburner carriage
- be compatible with all extruder combinations that are compatible with the stealthburner system, (CW1, CW2, Orbiter, LGX Lite, etc.)
- mount a Rapido HF/UHF hot end & Dragon SF/HF/UHF hot end
- improve overall cooling performance by accomodating very large fans
- provide uniform cooling from all directions
- be lightweight and easy to maintain

- work with klickyprobe & euclid probe.

**This mod is still a BETA. Expect issues - but let me know about them so I can fix them.**

**Feel free to contact me directly on discord if you would like to help me test this mod and provide feedback.**

# Gallery

### My setup:
My system specifications:
- Voron 2.4r2
- UHF rapido with CHT volcano nozzle
- Orbiter V2.0
- Euclid probe

A WS7040 blower can effectively cool volumetric flow rates beyond 70 mm^3/s (this is the limit of the hot end, NOT the cooling!).

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/194479013-b6fde3b8-cf25-49be-87e4-bf0bb4626d9a.jpeg">

### CFD results:

<img width="400" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/222349741-af51ee42-947d-4d13-abc0-36f03b5f4968.png"> <img width="400" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/222350137-e37b25a5-53a1-4d56-90b9-6fde59ddf052.png">
<img width="600" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/222349658-3f779d3e-316e-43d4-90a7-016135d2e329.png"> 


## Dragon SF/HF

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704723-2a31ad70-a9d7-409f-bbbe-7ab9de4505d6.png">
<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704734-c11211ae-4b3d-45fa-bcca-7a284825139d.png">

## Dragon UHF

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704761-73baafed-eb4d-4bbc-a65d-91168edb96f4.png">
<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704842-4c892ae8-7313-47ee-ab54-abd7306c677a.png">

## Rapido HF

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704859-1681f8d0-f31b-4c9e-9b91-c35490132e14.png">
<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704869-9e668f24-b935-4c70-a8e9-1339480363a3.png">

## Rapido UHF

<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704885-2a11518a-dcc6-4f44-9f16-5dac49e67290.png">
<img width="751" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/218704891-6dc8b409-11c5-4ee8-83e8-0532968b098a.png">

# Part Cooling Fan Options

There are a number of part cooling fan options to choose from, depending on your intended use case.

### 4028 fan

<img width="250" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/224202478-e5becb0b-ecc1-4771-b074-3288d9c18826.png">


A "medium" performance option is to use a 4028 fan on the end of the CPAP tube. This solution is best suited for ABS and similiar materials (or PLA but printing at slow speeds, aka <200mm/s) that do not require high amounts of part cooling. 

A 4028 to CPAP tube adapter part is included in the STL files folder. I have not developed a mount to attach the fan to the frame, but I intend to do this soon.

Recommended 4028 fans include:
- Sanyo 9GAX0412P3S001
- Delta FFB0412UHN-SM36

### 7040 blower fan

<img width="300" alt="Screen Shot 2022-06-23 at 6 24 17 PM" src="https://user-images.githubusercontent.com/12782053/224202438-7c1f9482-3080-46ef-9dcf-3d7adbacfff1.jpg">

A "high" performance is to use a 7040 blower fan on the end of the CPAP tube. This solution is best suited for printing PLA & PETG at low to very high speeds. It can print ABS, however it will likely be cooled more than required (due to the minimum fan speed of the blower) - and the ABS part strength will be decreased.

A 7040 blower fan mount can be found [here.](https://www.printables.com/model/324265-ws7040-centrifugal-blower-fan-mount)

I recommend the WS7040 along with the controller board. I purchased mine from [Trianglelab here.](https://www.aliexpress.com/item/1005003822117604.html)

# BOM
- 2510 hotend cooling fan. [I purchased this one.](https://www.aliexpress.com/item/33030471365.html)
- QTY:2,  2.5mm x 14mm self tapping screw, for 2510 fan.
- QTY:2 M3x4x5 heatset inserts
- QTY:2 M3x8mm SHCS DIN912
- QTY:2 M3x16mm SHCS DIN912
- QTY:2 M3x50mm SHCS DIN912
- Blower fan, see section above.

# Installation instructions 
- This mod uses the standard stealthburner X carriage parts. The back piece of the rapido toolhead mount is also used.
- This mod should work with all types of extruder mounting parts, including CW2 (however, I have not yet tested it). I use the orbiter V2 extruder mount found [here](https://github.com/sneakytreesnake/StealthOrbiter).
- Print the cooling duct with no supports, file in STL folder. Recommended to use 0.1mm layer height.
- Print the front & rear toolhead part with supports. 
- Only euclid and klicky probes are compatible at the moment. Use the offset klicky mount for HF hot ends, use the tall offset clock mount for UHF hot ends.


# Development Roadmap
1)[COMPLETE] - Proof of concept testing

2)[IN PROGRESS] - Beta testers needed!

3)[COMING SOON] - Rapido UHF release. Other hot ends will be released afterwards. 

# V2 Sneak Peek

Based on beta feedback, a V2 of the crowncooler is being developed and currently undergoing testing.


![CrownCoolerV2](https://user-images.githubusercontent.com/12782053/236075661-5eef9876-432e-4b2d-9f55-3736e35f87c8.jpg)
![CrownCoolerV2-1](https://user-images.githubusercontent.com/12782053/236075664-2ce9a560-bdc1-4e15-8e94-6d1b76e40ca8.jpg)
![CrownCoolerV2-2](https://user-images.githubusercontent.com/12782053/236075655-6a557129-4c38-425b-9006-fb8273492518.jpg)
![CrownCoolerV2-3](https://user-images.githubusercontent.com/12782053/236075658-a560ee25-6d28-445f-a76f-bb3479a3eab2.jpg)
![CrownCoolerV2-4](https://user-images.githubusercontent.com/12782053/236075660-1e88b1c0-aee8-4450-aa71-69d7574bdeb9.jpg)




# DC-power-supply-project
Designed and built a 30 V DC linear bench power supply

A power supply is a great tool for all electrical enthusiasts. My BCIT electrical engineering program included a 4-month course ELEX 1112: Engineering Tools, and a 4-week course ELEX 1102: Electronics Fabrication Tools and Techniques, in which I designed and built a DC linear bench power supply.

<img src=https://user-images.githubusercontent.com/93152842/190589401-83ad5bde-d4ca-45cb-93d9-78d321fd6c44.png>

*My bench power supply!*

I learned how to use AutoCAD 2022 to design the body chassis, Solidworks PCB to design the PCB electrical schematic, and Altium Designer to manually route and verify the PCB component layout. I also learned how to hand-solder SHT and TH components onto a PCB.

The power supply provides three DC voltage outputs when powered by a 120VAC 60Hz source. The rated DC output voltages are +5VDC (fixed), -15VDC (fixed), and +20VDC (variable). The rated current at each output is 1A.

## Parts list (Electrical)

| Ref Des | Value/PN | Description | Pkg | Qty |
| ------- | -------- | ----------- | --- | --- |
| C1,C2 | 3300uF, 20% | 25V, Al electrolytic | Radial | 2 |
| C3,C5 | 0.1uF, 20% | 50V, Al electrolytic | Radial | 2 |
| C4,C6 | 1uF, 20% | 50V, Al electrolytic | Radial | 2 |
| C7 | 2.2uF, 20% | 50V, Al electrolytic | Radial | 1 |
| D1,D2,D3,D4 | 1N4005 | 1A, 600V, General purpose | D0-41 | 4 |
| D5 | | Pilot light, LED, Red | | 1 |
| F1 | 375mA, 250V | Cartridge, Glass, Time delay | | 1 |
| J1 | | Banana jack, Red, Nut | | 1 |
| J2 | | Banana jack, White, Nut | | 1 |
| J3 | | Banana jack, Violet, Nut | | 1 |
| J4 | | Banana jack, Black, Nut | | 1 |
| P1 | 125V, 10A | 1.8m, 18AWG/3C, Grey | | 1 |
| R1 | 10R, 5% | 10W | Axial | 1 |
| R2,R4 | 390R, 5% | 1/4W | Axial | 2 |
| R3 | 5K, 10% | 1/2W, Linear | | 1 |
| S1 | 120V, 5A | SPST, Round rocker, Dot | | 1 |
| T1 | 33VCT/1A | 33V, Center tapped, 1A | | 1 |
| U1 | 7805 | Regulator, 1A, Fixed, 5V | TO220-3 | 1 |
| U2 | 317 | Regulator, 1.5A, Fixed, Variable | TO220-3 | 1 |
| U3 | 7915 | Regulator, 1A, Fixed, 15V | TO220-3 | 1 |


## Diagrams
 Reference designs were provided by BCIT. 
(1) <img src="https://user-images.githubusercontent.com/93152842/190590843-ea3c5b72-6e40-4e1c-a652-81fd0b2fae08.png" width=350>
(2) <img src="https://user-images.githubusercontent.com/93152842/190592248-6310b6a9-bc00-4940-9e85-5a9601dfdf29.png" width=350> 

(1) PCB artwork (2) PCB component locator

(3) <img src="https://user-images.githubusercontent.com/93152842/190596077-2c950d55-55ba-49c5-96e9-7ab760715a23.png" width=350>
(4) <img src="https://user-images.githubusercontent.com/93152842/190595726-69a82747-c126-45bc-b4cb-d207f05b121f.png" width=350> 

(3) Schematic diagram (4) Interconnect diagram 

(5) <img src="https://user-images.githubusercontent.com/93152842/190597803-3e283524-5fb2-40d6-ba60-df02986d3a21.png" width=350>
(6) <img src="https://user-images.githubusercontent.com/93152842/190599936-76331e98-bdf7-4b51-8ac7-9b269204edca.png" width=350>

(5) Plan view (6) An X-ray perspective view of 3D chassis using AutoCAD 2022

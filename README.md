# NeoGeoAES-3.5 PCB Reproduction

This repository contains a recreation of the main board PCB for NeoGeo AES
consoles. This recreation is based on the available schematics for the
NeoGeo AES and reverse engineering using scanned images of the original
board's copper layers, so should be a reasonably accurate reproduction.

![PCB](images/NeoGeoAES3_5_Front.png)


## PCB Production

Minimum track widths, clearances and via sizes are within the standard
offering of modern PCB fabricators. Development was done using JLCPCB and as
such the Gerber files are provided to their specification.

The design is verified to work as a 2-layer PCB.


## Bill of Materials

Most parts are marked on the board and it is expected that these will be reused
from a donor board. It is completely possible that your particular board uses
different (but compatible) parts so it's advisable to take photos before starting.
For a complete BOM, consult the KiCad project's BOM folder, there you will find a CSV file or a PDF.

[**PDF BOM**][BOM]

[**Interactive BOM**][IBOM]


List of components available from [**Mouser**][MOUSER], anything else use from the original board.

| Qty | Reference | Value | Mouser No. |
|:---------:|:-----:|:---------:|:-----------------:|
| 41 | "BF1, BF2, BF3, BF4, BF5, BF6, BF7, BF8, BF9, BF10, BF11, BF12, BF13, BF14, BF15, BF16, BF17, BF18, BF19, BF20, BF21, BF22, BF23, BF24, BF25, BF26, BF27, BF28, BF29, BF30, BF31, BF32, BF51, BF52, BF53, BF54, BF55, BF56, BF301, BF302, BF303" | ZBF253D | 80-B-06-R-25 |
| 19 | "C1, C2, C4, C5, C6, C7, C8, C11, C12, C20, C24, C25, C32, C34, C35, C41, C49, C113, C301" | 10uF | 667-ECA-1CM100I |
| 1 | C3 | 68pF | 810-FG28C0G2A680JNT6 |
| 7 | "C9, C10, C36, C37, C38, C39, C46" | 470uF/16v | 647-UHE1C471MPD6 |
| 2 | "C13, C14" | 272M | 80-MMK5272K63J01TA18 |
| 2 | "C22, C23" | 1nF | 810-FG28C0G1H102JNT6 |
| 3 | "C26, C27, C28" | 0.1uF | 810-FG26C0G1H104JNT0 |
| 1 | C29 | 100pF (82p) | 810-FG28C0G1H101JNT6 |
| 2 | "C30, C45" | 0.01uF | 810-FG28C0G1H103JNT0 |
| 1 | C31 | 39pF (30pF) | 810-FG28C0G1H390JNT6 |
| 6 | "C33, C42, C58, C59, C60, C201" | 100pF | 810-FG28C0G1H101JNT6 |
| 1 | C43 | 47pF | 810-FG28C0G1H101JNT6 |
| 3 | "C44, C50, C70" | 10nF | 810-FG28C0G1H103JNT0 |
| 1 | C47 | 2200uF/6.3v | 667-EEU-FC0J222S |
| 1 | C48 | 150pF | 810-FG28C0G1H151JNT6 |
| 27 | "C51, C63, C101, C102, C103, C104, C105, C106, C107, C108, C109, C110, C111, C112, C114, C115, C116, C117, C118, C119, C120, C121, C122, C123, C124, C125, C127" | 100nF | 810-FG26C0G1H104JNT0 |
| 2 | "C52, C54" | 30pF(CH) | 80-C322C300K3G5TA |
| 1 | C53 | 6pF | 810-FG28C0G1H060DNT6 |
| 1 | C55 | 20pF(CH) | 80-C317C200J5G |
| 2 | "C56, C67" | 220pF | 810-FG28C0G1H221JNT0 |
| 1 | C57 | 331pF | 810-FG28C0G1H331JNT6 |
| 2 | "C61, C62" | 221pF | 810-FG28C0G1H221JNT0 |
| 1 | C64 | 10pF(CH) | 810-FG28C0G1H100DNT6 |
| 1 | C65 | 39pF (CH) | 810-FG28C0G1H390JNT6 |
| 1 | C126 | 100uF | 667-ECA-1CM101I |
| 2 | "CN4, CN5" | AXC90020 | 587-395-100-524-204 |
| 1 | CN6 | 5535653-1 | 571-5535653-1 |
| 2 | "D1, D2" | SR340 | 583-SR340-T |
| 1 | D5 | LED | 604-WP7113ID5V |
| 1 | J4 | POWER JACK | 490-PJ-102B |
| 1 | L1 | 47uH | 530-SFAPI-470K-UL |
| 1 | L2 | 47uH | 530-SFAPI-470K-UL |
| 2 | "Q101, Q102" | 2SC1815 | 610-2SC1815 |
| 16 | "R1, R2, R3, R32, R36, R37, R38, R39, R40, R41, R42, R43, R45, R54, R55, R301" | 1K | 71-CMF501K0000FHEA |
| 3 | "R4, R5, R6" | 8.2K | 71-RN60D-F-8.2K |
| 3 | "R7, R11, R15" | 3.9K | 71-RN60D3901F |
| 3 | "R8, R12, R16" | 2.2K | 71-RN60D2201F |
| 4 | "R9, R13, R17, R66" | 470 | 71-RN60C4700F |
| 3 | "R10, R14, R18" | 220 | 71-RN60D2200F |
| 3 | "R19, R20, R21" | 150 | 71-RN60E1500F |
| 4 | "R28, R57, R68, R303" | 10K | 71-RN60E1002F |
| 1 | R29 | 47 | 71-RN60D47R0F |
| 2 | "R30, R31" | 4.7K | 71-RN60D4701F |
| 2 | "R33, R34" | 10 | 71-CMF5010R000FHEK |
| 3 | "R46, R49, R53" | 27K | 71-RN60D-F-27K |
| 2 | "R47, R48" | 47K | 71-RN60D4702F |
| 4 | "R50, R51, R52, R75" | 3K | 71-RN60D3001F |
| 1 | R56 | 820 | 71-RN60D8200F |
| 3 | "R58, R59, R60" | 6.8K | 71-RN60D6801F |
| 6 | "R62, R63, R64, R65, R401, R501" | 75 | 71-CMF5075R000FHEB |
| 2 | "R70, R72" | 1M | 71-RN60D-F-1M/R |
| 1 | R71 | 10 | 71-CMF5010R000FHEK |
| 1 | R74 | 220K | 71-RN60D2203F |
| 2 | "R101, R102" | 100K | 71-RN60E1003F |
| 1 | R302 | 30K | 71-RN60D-F-30K |
| 2 | "R402, R502" | 51K | 71-RN60D5102F |
| 2 | "R403, R503" | 15K | 71-CMF5015K000FHEK |
| 1 | RA1 | 4.7Kx4 | 652-4605X-1LF-47K |
| 2 | "RN1, RN2" | 22x4 | 652-4608X-2LF-22 |
| 1 | T1 | SH-302 | 80-SH-302 |
| 2 | "U8, U80" | 74HC04 | 595-SN74HC04N |
| 2 | "U9, U10" | 74LS273 | 595-SN74LS273N |
| 1 | U11 | 74LS05 | 595-SN74LS05N |
| 1 | U12 | 74LS06 | 595-SN74LS06N |
| 1 | U15 | 74LS244 | 595-SN74LS244N |
| 1 | U33 | 74AS04 | 595-SN74AS04N |
| 1 | U35 | 74HC259 | 595-SN74HC259N |
| 1 | U38 | 74HC32 | 595-SN74HC32N |
| 1 | X2 | 3.579545MHz | 815-AB-3.579545-B2 |

## 9V or 5V

The NeoGeo AES 3-5 could come configured as either 9V or 5V supply input.

My board is 9V which this repository is based on. Due to this I have marked on the schematics/BOM
which parts are not to populated if using 9V or 5V and by default the 5V circuit is N.F (Not Fitted).

C66 was also not populated.


## Jumper / Links

There are various links around the board.

* __NTSC1 / PAL2 - Only one of these should be populated, it would be very very very bad if both are populated
  as one links to GND and the other to VCC.__\
&nbsp;
* PAL1 and PAL2 - if your board is configured for PAL with the appropriate crystal, these should be populated
* NTSC1 - if your board is configured for NTSC, this should be populated with the appropriate crystal.
* 5863 / 5814 - depending on your memory type, one of these should be populated.
* J1 - BERR Signal into the CPU. Default is off.
* J2 - DOGE Signal into the NEO-B1. Default is off.
* J3 / J4 - This is for the EVEN signal to the LSPC2 chip. J3 is already enabled by default.


## Memory

* 5814 - The shorter of the RAM Chips, make sure to populate into socket to the far right and populate the correct
  jumper.
* 5863 - The longer of the RAM Chips, uses the whole socket. Populate the correct jumper.


## Thanks

  * Rob Taylor ([@PeepoUK](https://github.com/PeepoUK)) for doing most of
    the PCB layout.\
&nbsp;
  * Simon "Aergan" Lock ([@Aergan](https://github.com/Aergan)),\
    Cosam (@cosam_the_great),\
    Dennis (@PointerFunction),\
    Leo Oliveria (@leo__oliveira),\
    Zaxour 阿宅, (@zaxour),\
    Ian Cudlip (@grandoldian)\
    for their insights, support and testing of the prototype boards.\
&nbsp;
  * The rest of the Board Folk Team for their support and general
    coolness.\
&nbsp;
  * The [NeoGeo Development Wiki](https://wiki.neogeodev.org/) for making
    the original NeoGeo-2 Schematics available, and the people who maintain
    this site.\
&nbsp;


## Legal

As the product of this project is a replica of a proprietary product, the
the author makes no claim of copyright to the schematics nor PCB layouts and
releases these into the public domain, solely for the purposes of study and
historical preservation.

You are free to produce PCBs based on this project's designs at your own risk
and without limitation, for your own use or for sale and/or repair at a
reasonable price. Attribution is appreciated. The authors are not obliged to
provide support of any kind.

Under no circumstances will the authors be held responsible or liable in any
way for losses, damages or costs resulting from the use of the information
and/or resources of this project.

The resources are provided "as-is" without warranty of any kind, either
expressed or implied, including, but not limited to, the implied warranties
of merchantability and fitness for a particular purpose.

[IBOM]: http://htmlpreview.github.io/?https://raw.githubusercontent.com/Board-Folk/NeoGeoAES-3.5/main/bom/NeoGeo-AES-3_5.html

[BOM]: http://htmlpreview.github.io/?https://raw.githubusercontent.com/Board-Folk/NeoGeoAES-3.5/main/bom/NeoGeoAES3_5-BOM.pdf

[MOUSER]: http://htmlpreview.github.io/?https://raw.githubusercontent.com/Board-Folk/NeoGeoAES-3.5/main/bom/NeoGeoAES3_5-MouserParts.csv

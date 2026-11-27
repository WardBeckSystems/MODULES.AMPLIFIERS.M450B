# M450B Program Summing Amplifier · Amplifiers

Ward-Beck Systems M450B, 1979|12. Wiki page: [M450B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M450B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 9 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 19 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 109 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 21 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [17 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1979 - M450B - Program - Summing Amplifier.pdf](MANUALS/1979%20-%20M450B%20-%20Program%20-%20Summing%20Amplifier.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 24 to 40 dB _ Unity, with external pair of ISk onm resistors. |
| **Noise** | (20 Hz to 20 kHz) -68 dBm (at 40 dB gain). -82 dBm (at unity gain) |
| **Input impedance** | Sk ohms. 30k ohms (with external pair of 1S5k ohm resistors) |
| **Output isolation** | (not applicable) 90 dB or better from 30 Hz [0 20 kHz. Maximum Input Level -10 to +6 dBm. +30 dBm. Used a5 PROGRAM Or sumMING AMPLIFIER |
| **Frequency response** | +/ -0.25 dB from 20 Hz La 20 kHz. |
| **Harmonic distortion** | Less than 0.27 THD from 20 Hz [0 20 kHz. |
| **Source impedance** | 600 ohms maximum, balanced Maximum Output Level +30 dBm into 600 ohm Load, balanced |
| **Output impedance** | Less than 35 ohms, balanced. |
| **Load impedance** | 600 ohms minimum |
| **Phasing** | Low number terminals of input and outpul are in phase |
| **Power requirements** | +/ -25 volts dc, L0 mA quiescent currenia 100 mA at +30 dBm output into 600 ohms. |
| **Ambient temperature** | to 60 degrees Celsius. |
| **Dimensions** | 1.1&quot; wide X 3.5&quot; high X 7.0&quot; deep (28 mm X 89 mm X 178 mm) |

## Circuit description

From [1979 - M450B - Program - Summing Amplifier.pdf](MANUALS/1979%20-%20M450B%20-%20Program%20-%20Summing%20Amplifier.pdf) pages 6-11 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The MLSOB is direct replacement for the M4so dual purpose Program/ Summing Amplifier_ When used 29 suMming amplifier, the balanced inpul signal is applied via external summing resistors to pins and 5. In the program amplifier diode, the input signal is applied [0 pins and of the edge connector and proceeds via R1 and R2 to the pre= amplifiers, thus presenting an input impedance of approximately Sk ohms to the source The input connects to [Wo preamplifiers, one consisting of 01 through 03, the other 04 through 08 From the output of the upper inverting amplifier the signal proceeds [0 the input of the lower amplifier via R10, RII and C6_ Rio Serves as differential control to equalize any smal| gain differences between the Lwo amplifier sections, resulting in optimum common mode rejection. When used as summing amplifier, the M4SOB is normally operating at unity gain, whereas in the program amplifier mode the gain maybe adjusted anywhere between 24 and 40 dB Al gain changes are achieved by external resistance strapping On pins 9, 10 and 11 on the module connector, affecting the feedback loop within the lower preamplifier. C10 couples the output of the preamplifier Lathe output section. 22,013,014,015 and 016 represent the lower half of the output amplifier. 12 dB/octave low-pass filter consisting of R22, R23, R24, ci, C13 and C14 limits the bandwidth beyond the audio passband One half of the output signal is derived from the lower half of the output amplifier and is brought out Lo pin 13 via C24, L2 and R56. The input signal ior the second output amplifier half is routed via R35 to pin of 21, followed by 09 through 012. C23 LI and R55 couple the output of this Part of the amplifier to pin 12 The actively balanced output of the unit, appearing at Pins 12 and 13, is capable of delivering Watt into 600 ohm load.

CIRcUIT DESCRIPTION M4SoB PROGRAM/SUMMING AMPLIFIER The bipolar +/ -25 volt supply voltages applied to pins 1, and 15 are coupled via isolation diodes CRS and CR6 [0 C25 and C26 Additional filter networks reduce the supply voltage to +/ -18 and +/ -16 volts to operate the preamplifiers J5 wel / a5 the integrated circuits As result of the symmetry Ot the circuit, the dc voltages at the collector ot 03, a5 wel as the junctiuns R20/R21, RL4/RL5 and R32/R33 wili be 4L potential of volts +7 -0.5 volt. In the quiescent state, the amplifier requires current of approximately 40 MA, rising to 80 to 100 MA at full outpul, delivering +30 dBm into 600 ohm load

GAIn ADJUSTMENT

Used d5

**PROGRAM AMPLIFIER**

Resistor or pot between Pins 9 &amp; 10

3 = 8

Resistor or pot between pins 10 &amp; M1

Resistance ink ohms

Used a$ SUMMING AMPLIFIER 4 500 ohm trim Pot connected between pins 10 and 11 wilt cause the amplifier to operate at unity gain with trim adjustment of t1 dB

PARTS List

**C1 C2 C3 C4 C5**

Capacitor 330 uF/6 Kemet

**T390F 337M006A5**

delete 47 PF 3.3 pF Philips 2222-638-70479 2222-638-09338 C6 C7 c8 C9 C10 56 pF delete delete 3.3 PF 33 UF/10 2222-638-70569

**2222-638-09338 T3900336M01OAS**

Kemc t

**C1I C12 C13 C14 C15**

2200 PF 10 pF 33 pF 220 pF 33 PF Aselco Philips ca92-MC-222M 2222-638-10109 2222-638-58339 2222-630-03221 2222-638-58339

**C16 C17 C18 C19 C20**

22 pF 10 uF/25 10 pF 33 PF 2222-638-58229 T39OC | OGMO25AS 2222-638-10109 2222-638-58339 Kemet Philips

**C21 C22 C23 C24 C25**

22pF 10 uF/25 220 uF/10

**2222-638-58229 T390C106MO25AS T390F227M010AS**

Kemet 22 uF/25 Philips

**L26ETF22**

C26 C27 C28 C29 C30 10 uF/25 Kemet

**T390C 106M02545**

C31 C32 c33

**33 PF 0.68/35 0.68/35**

Philips

**CRI CR2 CR3**

Diode Fairchild

**1N4148**

PARTS LisT MASON PROGRAM/suMM NG AMPLIFIER

**CRL CRS CR6**

Motorola Motorola

**INLOO3 INLOO3**

Diode

**LI L2**

Choke 100 uH

**WBS 23-001**

01 02 03 04 05 Transistor National

**PN3645 ZNLLOI**

06 07 08 09 010

**PN3645 PN3569 PN3645 PN3569 ZN3645**

011 012 013 014 015 TIP29B TIP3OB PN3569 2N3645 Tip298 National Texas

**RI R2 RJ R4 R5**

Resistor 1/Lw 57 2K7 2K7 15k T5k 8K2 Philips R6 R7 R8 R9 R10 47K 5k 22 2K7 2K Trim Pot Piher PT TOv 2k Ri Ri2 R13 R14 R1S Resistor 1/4w 57 7K5 3k3 220 4k? 47K Philips

Texas

</details>

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbTk5RHFidnYyNUk/view?resourcekey=0-wLKDuGv9hL1FnXHKKH1z6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbTk5RHFidnYyNUk&resourcekey=0-wLKDuGv9hL1FnXHKKH1z6g" width="240" alt="1979 - M450B - 450-02-003 - PROGRAMISUMMING AMPLIFIER.jpg"></a><br><sub>1979|12 · 450-02-003 - PROGRAMISUMMING AMPLIFIER · <a href="SCHEMATICS/1979%20-%20M450B%20-%20450-02-003%20-%20PROGRAMISUMMING%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX3BGd1dEa1FxUjQ/view?resourcekey=0-ZazvHduNVjtkf2Lx5yjP-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX3BGd1dEa1FxUjQ&resourcekey=0-ZazvHduNVjtkf2Lx5yjP-g" width="240" alt="1979 - M450B - 450-06-003 - MASOB ENG.jpg"></a><br><sub>1979|12 · 450-06-003 - MASOB ENG · <a href="SCHEMATICS/1979%20-%20M450B%20-%20450-06-003%20-%20MASOB%20ENG%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd29zb0NZWlJPN2M/view?resourcekey=0-SxnXCKUPM0mCVwzFNu0CCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd29zb0NZWlJPN2M&resourcekey=0-SxnXCKUPM0mCVwzFNu0CCA" width="240" alt="1979 - M450B - P15 - Pin Outs.jpg"></a><br><sub>1979|12 · P15 - Pin Outs · <a href="PINOUTS/1979%20-%20M450B%20-%20P15%20-%20Pin%20Outs%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M450B - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 3 pinout pictures (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 15 of 15 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +25 V | power |  | high |
| 2 | N/C | nc |  | high |
| 3 | SUMMING INPUT | in | SUMMING INPUT | high |
| 4 | INPUT (SUMMING + PROGRAM) | in | PROGRAM INPUT | high |
| 5 | SUMMING INPUT | in | SUMMING INPUT | high |
| 6 | PROGRAM INPUT | in | PROGRAM INPUT | high |
| 7 | INPUT SHIELD | shield | PROGRAM INPUT shield | high |
| 8 | COMMON | ground |  | high |
| 9 | GAIN SET | strap | GAIN SET | high |
| 10 | GAIN SET | strap | GAIN SET | high |
| 11 | GAIN SET | strap | GAIN SET | high |
| 12 | OUTPUT | out | OUTPUT | high |
| 13 | OUTPUT | out | OUTPUT | high |
| 14 | N/C | nc |  | high |
| 15 | -25 V | power |  | high |

**Straps:** GAIN SET: P1-9 P1-10 P1-11

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeVBRajhXb3I1TE0/view?resourcekey=0-qNR9q3_pKuwsDqcdj2EPEg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeVBRajhXb3I1TE0&resourcekey=0-qNR9q3_pKuwsDqcdj2EPEg" width="240" alt="1979 - M450B - P01 - Cover.jpg"></a><br><sub>1979|12 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWcyR2VtbERULU0/view?resourcekey=0-Ef-D_JKIOLvQlCwSTDzeOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWcyR2VtbERULU0&resourcekey=0-Ef-D_JKIOLvQlCwSTDzeOQ" width="240" alt="1979 - M450B - P02.jpg"></a><br><sub>1979|12 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFJlelZFam1qdkU/view?resourcekey=0-HgH6u0t8VGCMwVcX3bz8eQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFJlelZFam1qdkU&resourcekey=0-HgH6u0t8VGCMwVcX3bz8eQ" width="240" alt="1979 - M450B - P03 - TOC.jpg"></a><br><sub>1979|12 · P03 - TOC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFNMSi1oSUJ4R0k/view?resourcekey=0-R-kKznP7k1TH6Nw-3pl9rg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFNMSi1oSUJ4R0k&resourcekey=0-R-kKznP7k1TH6Nw-3pl9rg" width="240" alt="1979 - M450B - P04 - Warranty.jpg"></a><br><sub>1979|12 · P04 - Warranty</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0xlVERyTUo0NDQ/view?resourcekey=0-83RHMqPj2mY_EROSvmCu4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0xlVERyTUo0NDQ&resourcekey=0-83RHMqPj2mY_EROSvmCu4A" width="240" alt="1979 - M450B - P05 - 1-1.jpg"></a><br><sub>1979|12 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0dwWnlrYVp1Z2M/view?resourcekey=0-1rQCmBxqdjM4zGgjO76OEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0dwWnlrYVp1Z2M&resourcekey=0-1rQCmBxqdjM4zGgjO76OEQ" width="240" alt="1979 - M450B - P06 - 2-1.jpg"></a><br><sub>1979|12 · P06 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQUx2d2NXc2RiUUk/view?resourcekey=0-IS_kKaLE2ZFc8PDPIUSCBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQUx2d2NXc2RiUUk&resourcekey=0-IS_kKaLE2ZFc8PDPIUSCBg" width="240" alt="1979 - M450B - P07 - 2-2.jpg"></a><br><sub>1979|12 · P07 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcHh6d3hiVFlOWms/view?resourcekey=0-Tcrh2_5etYq5XKXQmw1FTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcHh6d3hiVFlOWms&resourcekey=0-Tcrh2_5etYq5XKXQmw1FTQ" width="240" alt="1979 - M450B - P08 - 3-1.jpg"></a><br><sub>1979|12 · P08 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSE5VQ1ZBYjR4d00/view?resourcekey=0-S5sMUflJHvZVyPbAQw0IyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSE5VQ1ZBYjR4d00&resourcekey=0-S5sMUflJHvZVyPbAQw0IyA" width="240" alt="1979 - M450B - P09 - 4-1.jpg"></a><br><sub>1979|12 · P09 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNURqU1hITEdFSk0/view?resourcekey=0-YEOyCbuGgeLppZ73eHLR8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNURqU1hITEdFSk0&resourcekey=0-YEOyCbuGgeLppZ73eHLR8Q" width="240" alt="1979 - M450B - P10 - 4-2.jpg"></a><br><sub>1979|12 · P10 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeTljYVZuWVUtdzA/view?resourcekey=0-fAsETFw_iZ1GrxzYWpR0Gw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeTljYVZuWVUtdzA&resourcekey=0-fAsETFw_iZ1GrxzYWpR0Gw" width="240" alt="1979 - M450B - P11 - 4-3.jpg"></a><br><sub>1979|12 · P11 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXA5aGRTSnVMMEk/view?resourcekey=0-btXjLh5E1F4VktJoWs8d9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXA5aGRTSnVMMEk&resourcekey=0-btXjLh5E1F4VktJoWs8d9Q" width="240" alt="1979 - M450B - P12 - 4-4.jpg"></a><br><sub>1979|12 · P12 - 4-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZWp5T3ZHOC02ZjA/view?resourcekey=0-VG9iSPQ8nsbnxrZ-bSJFAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZWp5T3ZHOC02ZjA&resourcekey=0-VG9iSPQ8nsbnxrZ-bSJFAw" width="240" alt="1979 - M450B - Program - Summing Amplifier.pdf"></a><br><sub>1979|12 · Program - Summing Amplifier</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNEcyMjh1eW54RmM/view?resourcekey=0-8bbsgZHJML8kMqdRmVRsnw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNEcyMjh1eW54RmM&resourcekey=0-8bbsgZHJML8kMqdRmVRsnw" width="240" alt="1979 - M450B - WBS test procedures 3.jpeg"></a><br><sub>1979|12 · WBS test procedures 3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmZad1QxcloxNUk/view?resourcekey=0-RWbHB_i0g90yIP-JpItr4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmZad1QxcloxNUk&resourcekey=0-RWbHB_i0g90yIP-JpItr4Q" width="240" alt="1979 - M450B - WBS test procedures 4.jpeg"></a><br><sub>1979|12 · WBS test procedures 4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY1hGRkNldlluNEE/view?resourcekey=0-anQhU95Of0ETH_Nl2MiLrg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY1hGRkNldlluNEE&resourcekey=0-anQhU95Of0ETH_Nl2MiLrg" width="240" alt="1979 - M450B - WBS test procedures 5.jpeg"></a><br><sub>1979|12 · WBS test procedures 5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHJ3R1Z2cFNWWG8/view?resourcekey=0-xq5rHCbZMwsbb7Yc3PtNpg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHJ3R1Z2cFNWWG8&resourcekey=0-xq5rHCbZMwsbb7Yc3PtNpg" width="240" alt="1979 - M450B - WBS test procedures 6.jpeg"></a><br><sub>1979|12 · WBS test procedures 6</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1979|12 · Program - Summing Amplifier (2)](https://drive.google.com/file/d/0B0yR0b5T78SKcXhfbkdHZ005Um8/view?resourcekey=0-nC8LZYrqEhrfTSAe3iAMrw)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1979 - M450B - 450-02-003 - PROGRAMISUMMING AMPLIFIER.kicad_sch](KICAD/1979%20-%20M450B%20-%20450-02-003%20-%20PROGRAMISUMMING%20AMPLIFIER.kicad_sch)
- [1979 - M450B - Program - Summing Amplifier p10.kicad_sch](KICAD/1979%20-%20M450B%20-%20Program%20-%20Summing%20Amplifier%20p10.kicad_sch)
- [1979 - M450B - Program - Summing Amplifier p13.kicad_sch](KICAD/1979%20-%20M450B%20-%20Program%20-%20Summing%20Amplifier%20p13.kicad_sch)
- [M450B.kicad_sym](KICAD/M450B.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

# TEDAC Wiring Reference

## Conventions

TEDAC buttons/switches are named left to right, top to bottom on their respective devices. For example:

* TFP-T1MP TEDAC Faceplate, Top row position 1 (left) momentary press
* TFP-L2RP TEDAC Faceplate, Left row postion 2 (2nd from top), rotary press
* TFP-L2R[ABC] TEDAC Faceplate, Left row postion 2 (2nd from top), rotary encoder pin A, B or C
* all matrixed pins on a specific faceplate PCB are on the same row for ease of wiring
* TGL-01BMP TEDAC Grip Left, input 01 (button) momentary press
* TGL-02SM[FA] TEDAC Grip Left, input 02 (switch) momentary forward/aft
* TGL-03HM[FALRP] TEDAC Grip Left, input 03 (hat) momentary forward/aft/left/right/press
* TGL-04S[FCA] TEDAC Grip Left, input 04 (switch) forward/center/aft
* TGL-06J[XYP] TEDAC Grip Left, input 06 (joystick) X/Y/press

All matrix pins on a specific grip switch are on the same matrix row for ease of wiring

## Input Lists

### Faceplate

| P.PIN    | FUNCTION    | P.HDR     | MATRIX ROW/COL | M.HDR | MEGA PIN(S) |
| -------- | ----------- | --------- | -------------- | ----- | ----------- |
| TFP-T1MP | TAD         | JP1-TOP   | 1-1            | TFPT  |             |
| TFP-T2MP | FCR         | JP1-TOP   | 1-2            | TFPT  |             |
| TFP-T3MP | PNV         | JP1-TOP   | 1-3            | TFPT  |             |
| TFP-T4MP | G/S         | JP1-TOP   | 1-4            | TFPT  |             |
| TFP-T5RP | DayNtOff NF | JP1-TOP   | 1-5            | TFPT  |             |
| TFP-T5RA | DayNtOff A  | JST1-TOP  | -              | TFP01 |             |
| TFP-T5RB | DayNtOff B  | JST1-TOP  | -              | TFP01 |             |
| TFP-T5RC | DayNtOff C  | JST1-TOP  | -              | TFP01 |             |
| TFP-L1RP | LEV NF      | JP2-LEFT  | 2-1            | TFPL  |             |
| TFP-L1RA | LEV A       | JST2-LEFT | -              | TFP02 |             |
| TFP-L1RB | LEV B       | JST2-LEFT | -              | TFP02 |             |
| TFP-L1RC | LEV C       | JST2-LEFT | -              | TFP02 |             |
| TFP-L2RP | GAIN NF     | JP2-LEFT  | 2-2            | TFPL  |             |
| TFP-L2RA | GAIN A      | JST3-LEFT | -              | TFP03 |             |
| TFP-L2RB | GAIN B      | JST3-LEFT | -              | TFP03 |             |
| TFP-L2RC | GAIN C      | JST3-LEFT | -              | TFP03 |             |
| TFP-L3MP | R/F UP      | JP3-LEFT  | 2-3            | TFPL  |             |
| TFP-L4MP | R/F DOWN    | JP3-LEFT  | 2-4            | TFPL  |             |
| TFP-L5MP | EL UP       | JP3-LEFT  | 2-5            | TFPL  |             |
| TFP-L6MP | EL DOWN     | JP3-LEFT  | 2-6            | TFPL  |             |
| TFP-R1MP | SYM UP      | JP4-RIGHT | 3-1            | TFPR  |             |
| TFP-R2MP | SYM DOWN    | JP4-RIGHT | 3-2            | TFPR  |             |
| TFP-R3MP | BRT UP      | JP4-RIGHT | 3-3            | TFPR  |             |
| TFP-R4MP | BRT DOWN    | JP4-RIGHT | 3-4            | TFPR  |             |
| TFP-R5MP | CON UP      | JP5-RIGHT | 3-5            | TFPR  |             |
| TFP-R6MP | CON DOWN    | JP5-RIGHT | 3-6            | TFPR  |             |
| TFP-R7MP | * DEFAULT   | JP5-RIGHT | 3-7            | TFPR  |             |
| TFP-B1MP | AZ LEFT     | JP6-BOT   | 4-1            | TFPB  |             |
| TFP-B2MP | AZ RIGHT    | JP6-BOT   | 4-2            | TFPB  |             |
| TFP-B3MP | MULTI B1    | JP6-BOT   | 4-3            | TFPB  |             |
| TFP-B4MP | MULTI B2    | JP7-BOT   | 4-4            | TFPB  |             |
| TFP-B5MP | MULTI B3    | JP7-BOT   | 4-5            | TFPB  |             |
| TFP-B6MP | MULTI B4    | JP7-BOT   | 4-6            | TFPB  |             |

### Grip Left

| P.PIN     | FUNCTION    | P.HDR | MATRIX ROW/COL | M.HDR | MEGA PIN(S) |
| --------- | ----------- | ----- | -------------- | ----- | ----------- |
| TGL-01BMP | VIDEO REC   | -     |                | TGL01 |             |
| TGL-02SMF | IAT EN/ACT  | -     |                | TGL02 |             |
| TGL-02SMA | IAT OFS     | -     |                | TGL02 |             |
| TGL-03HMF | TADS FOV Z  | -     |                | TGL03 |             |
| TGL-03HMA | TADS FOV M  | -     |                | TGL03 |             |
| TGL-03HML | TADS FOV N  | -     |                | TGL03 |             |
| TGL-03HMR | TADS FOV W  | -     |                | TGL03 |             |
| TGL-03HMP | TADS FOV NF | -     |                | TGL03 |             |
| TGL-04SF  | SSEL FLIR   | -     |                | TGL04 |             |
| TGL-04SC  | SSEL DTV    | -     |                | TGL04 |             |
| TGL-04SA  | SSEL DVO NF | -     |                | TGL04 |             |
| TGL-05HMF | FCR GTM     | -     |                | TGL05 |             |
| TGL-05HMA | FCR ATM     | -     |                | TGL05 |             |
| TGL-05HML | FCR TPM     | -     |                | TGL05 |             |
| TGL-05HMR | FCR RMAP    | -     |                | TGL05 |             |
| TGL-05HMP | FCR NF      | -     |                | TGL05 |             |
| TGL-06JX  | CURSOR X    | -     |                | TGL06 |             |
| TGL-06JY  | CURSOR Y    | -     |                | TGL06 |             |
| TGL-06JP  | CURSOR ENT  | -     |                | TGL06 |             |
| TGL-07HMF | WAS G       | -     |                | TGL07 |             |
| TGL-07HMA | WAS A NF    | -     |                | TGL07 |             |
| TGL-07HML | WAS R       | -     |                | TGL07 |             |
| TGL-07HMR | WAS M       | -     |                | TGL07 |             |
| TGL-07HMP | WAS NF      | -     |                | TGL07 |             |
| TGL-08BMP | CURSOR L/R  | -     |                | TGL08 |             |
| TGL-09SMF | POS STORE   | -     |                | TGL09 |             |
| TGL-09SMA | POS UPD     | -     |                | TGL09 |             |
| TGL-10BMP | WPN TRIG    | -     |                | TGL10 |             |
| TGL-11SMF | FCR S-SCAN  | -     |                | TGL11 |             |
| TGL-11SMA | FCR C-SCAN  | -     |                | TGL11 |             |
| TGL-12BMP | CUED        | -     |                | TGL12 |             |
| TGL-13BMP | CAGE NF     | -     |                | TGL13 |             |
| TGL-14BMP | LMC         | -     |                | TGL14 |             |

### Grip Right

| P.PIN      | FUNCTION        | P.HDR | MATRIX ROW/COL | M.HDR | MEGA PIN(S) |
| ---------- | --------------- | ----- | -------------- | ----- | ----------- |
| TGR-01SF   | LST MODE A      | -     |                | TGR01 |             |
| TGR-01SC   | LST MODE O      | -     |                | TGR01 |             |
| TGR-01SA   | LST MODE M      | -     |                | TGR01 |             |
| TGR-02HMF  | FCR SCAN Z      | -     |                | TGR02 |             |
| TGR-02HMA  | FCR SCAN M      | -     |                | TGR02 |             |
| TGR-02HML  | FCR SCAN N      | -     |                | TGR02 |             |
| TGR-02HMR  | FCR SCAN W      | -     |                | TGR02 |             |
| TGR-02HMP  | FCR SCAN NF     | -     |                | TGR02 |             |
| TGR-03BMP  | C-SCOPE         | -     |                | TGR03 |             |
| TGR-04BMP  | FLIR POL        | -     |                | TGR04 |             |
| TGR-05SF   | IAT POL W       | -     |                | TGR05 |             |
| TGR-05SC   | IAT POL A       | -     |                | TGR05 |             |
| TGR-05SA   | IAT POL B       | -     |                | TGR05 |             |
| TGR-06HMF  | SIGHT HMD       | -     |                | TGR06 |             |
| TGR-06HMA  | SIGHT LINK      | -     |                | TGR06 |             |
| TGR-06HML  | SIGHT FCR       | -     |                | TGR06 |             |
| TGR-06HMR  | SIGHT TADS      | -     |                | TGR06 |             |
| TGR-06HMP  | SIGHT NF        | -     |                | TGR06 |             |
| TGR-07JX   | TFC X           | -     |                | TGR07 |             |
| TGR-07JY   | TFC Y           | -     |                | TGR07 |             |
| TGR-07JP   | TFC NF          | -     |                | TGR07 |             |
| TGR-08BMP  | SIGHT SLAVE     | -     |                | TGR08 |             |
| TGR-09BMP  | FCR ZOOM        | -     |                | TGR09 |             |
| TGR-10BMP1 | LRFD TRIG DET 1 | -     |                | TGR10 |             |
| TGR-10BMP2 | LRFD TRIG DET 2 | -     |                | TGR10 |             |
| TGR-11SMF  | MTT PROM NEXT   | -     |                | TGR11 |             |
| TGR-11SMA  | MTT PROM NEXT   | -     |                | TGR11 |             |
| TGR-12BMP  | CURSOR ENT      | -     |                | TGR12 |             |
| TGR-13BMP  | HDD NF          | -     |                | TGR13 |             |
| TGR-14BMP  | MSL ADV         | -     |                | TGR14 |             |

## Header List

| HEADER    | TYPE             | LOCATION             | PURPOSE                               |
| --------- | ---------------- | -------------------- | ------------------------------------- |
| JP1-TOP   | 5x2 Dupont Male  | Faceplate Top PCB    | Faceplate Top Buttons                 |
| JP2-LEFT  | 2x2 Dupont Male  | Faceplate Left PCB   | Faceplate Left Rotary Buttons         |
| JP3-LEFT  | 4x2 Dupont Male  | Faceplate Left PCB   | Faceplate Left Buttons                |
| JP4-RIGHT | 4x2 Dupont Male  | Faceplate Right PCB  | Faceplate Right Upper Buttons         |
| JP5-RIGHT | 3x2 Dupont Male  | Faceplate Right PCB  | Faceplate Right Lower Buttons         |
| JP6-BOT   | 3x2 Dupont Male  | Faceplate Bottom PCB | Faceplate BottomL Buttons             |
| JP7-BOT   | 3x2 Dupont Male  | Faceplate Bottom PCB | Faceplate BottomR Buttons             |
| JST1-TOP  | JST XH x3        | Faceplate Top PCB    | Faceplate Rotary 1                    |
| JST2-LEFT | JST XH x3        | Faceplate Left PCB   | Faceplate Rotary 2                    |
| JST3-LEFT | JST XH x3        | Faceplate Left PCB   | Faceplate Rotary 3                    |
| TFPT      | 5x2 Dupont Male  | Master PCB           | Master for Faceplate Top              |
| TFPL      | 6x2 Dupont Male  | Master PCB           | Master for Faceplate Left             |
| TFPR      | 7x2 Dupont Male  | Master PCB           | Master for Faceplate Right            |
| TFPB      | 6x2 Dupont Male  | Master PCB           | Master for Faceplate Bottom           |
| TFP01     | JST XH x3        | Master PCB           | Master for Faceplate Rotary 1         |
| TFP02     | JST XH x3        | Master PCB           | Master for Faceplate Rotary 2         |
| TFP03     | JST XH x3        | Master PCB           | Master for Faceplate Rotary 3         |
| TGL01     | JST XH x2        | Master PCB           | Master for Left Grip Switch 1         |
| TGL02     | JST XH x3        | Master PCB           | Master for Left Grip Switch 2         |
| TGL03     | JST XH x6        | Master PCB           | Master for Left Grip Switch 3         |
| TGL04     | JST XH x4        | Master PCB           | Master for Left Grip Switch 4         |
| TGL05     | JST XH x6        | Master PCB           | Master for Left Grip Switch 5         |
| TGL06     | JST XH x4        | Master PCB           | Master for Left Grip Switch 6         |
| TGL07     | JST XH x6        | Master PCB           | Master for Left Grip Switch 7         |
| TGL08     | JST XH x2        | Master PCB           | Master for Left Grip Switch 8         |
| TGL09     | JST XH x3        | Master PCB           | Master for Left Grip Switch 9         |
| TGL10     | JST XH x2        | Master PCB           | Master for Left Grip Switch 10        |
| TGL11     | JST XH x3        | Master PCB           | Master for Left Grip Switch 11        |
| TGL12     | JST XH x2        | Master PCB           | Master for Left Grip Switch 12        |
| TGL13     | JST XH x2        | Master PCB           | Master for Left Grip Switch 13        |
| TGL14     | JST XH x2        | Master PCB           | Master for Left Grip Switch 14        |
| TGR01     | JST XH x4        | Master PCB           | Master for Right Grip Switch 1        |
| TGR02     | JST XH x6        | Master PCB           | Master for Right Grip Switch 2        |
| TGR03     | JST XH x2        | Master PCB           | Master for Right Grip Switch 3        |
| TGR04     | JST XH x2        | Master PCB           | Master for Right Grip Switch 4        |
| TGR05     | JST XH x4        | Master PCB           | Master for Right Grip Switch 5        |
| TGR06     | JST XH x6        | Master PCB           | Master for Right Grip Switch 6        |
| TGR07     | JST XH x4        | Master PCB           | Master for Right Grip Switch 7        |
| TGR08     | JST XH x2        | Master PCB           | Master for Right Grip Switch 8        |
| TGR09     | JST XH x2        | Master PCB           | Master for Right Grip Switch 9        |
| TGR10     | JST XH x3        | Master PCB           | Master for Right Grip Switch 10       |
| TGR11     | JST XH x3        | Master PCB           | Master for Right Grip Switch 11       |
| TGR12     | JST XH x2        | Master PCB           | Master for Right Grip Switch 12       |
| TGR13     | JST XH x2        | Master PCB           | Master for Right Grip Switch 13       |
| TGR14     | JST XH x2        | Master PCB           | Master for Right Grip Switch 14       |
| MATRIX    | 10x2 Dupont Male | Master PCB           | 10x10 Matrix Master to Mega           |
| ENCS      | 7x1 Dupont Male  | Master PCB           | 6 + 1GND Rotary Enc Master to Mega    |
| AXES      | 5x1 Dupont Male  | Master PCB           | 4 + 1GND Joystick Axes Master to Mega |
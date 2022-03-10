# TEDAC Wiring Reference

## Conventions

TEDAC faceplate buttons are named left to right, top to bottom. For example:
* TFP-T1MP TEDAC Faceplate, Top row position 1 (left) momentary press
* TFP-L2RP TEDAC Faceplate, Left row postion 2 (2nd from top), rotary press
* TFP-L2R[ABC] TEDAC Faceplate, Left row postion 2 (2nd from top), rotary encoder pin A, B or C
* all matrixed pins on a specific faceplate PCB are on the same row for ease of wiring

TEDAC grip buttons/switches are also named left to right, top to bottom. Examples:
* TGL-01BMP TEDAC Grip Left, input 01 (button) momentary press
* TGL-02SM[FA] TEDAC Grip Left, input 02 (switch) momentary forward/aft
* TGL-03HM[FALRP] TEDAC Grip Left, input 03 (hat) momentary forward/aft/left/right/press
* TGL-04S[FCA] TEDAC Grip Left, input 04 (switch) forward/center/aft
* TGL-06J[XYP] TEDAC Grip Left, input 06 (joystick) X/Y/press
* All matrix pins on a specific grip switch are on the same matrix row for ease of wiring

## Input List

| P.PIN     | FUNCTION    | P.CONN    | MATRIX ROW/COL | M.CONN | MEGA PIN(S) |
|-----------|-------------|-----------|----------------|--------|-------------|
| TFP-T1MP  | TAD         | JP1-TOP   | 1-1            | TFPT   | |
| TFP-T2MP  | FCR         | JP1-TOP   | 1-2            | TFPT   | |
| TFP-T3MP  | PNV         | JP1-TOP   | 1-3            | TFPT   | |
| TFP-T4MP  | G/S         | JP1-TOP   | 1-4            | TFPT   | |
| TFP-T5RP  | DayNtOff NF | JP1-TOP   | 1-5            | TFPT   | |
| TFP-T5RA  | DayNtOff A  | JST1-TOP  | -              | TFPT   | |
| TFP-T5RB  | DayNtOff B  | JST1-TOP  | -              | TFPT   | |
| TFP-T5RC  | DayNtOff C  | JST1-TOP  | -              | TFPT   | |
| TFP-L1RP  | LEV NF      | JP2-LEFT  | 2-1            | TFPL   | |
| TFP-L1RA  | LEV A       | JST2-LEFT | -              | TFPL   | |
| TFP-L1RB  | LEV B       | JST2-LEFT | -              | TFPL   | |
| TFP-L1RC  | LEV C       | JST2-LEFT | -              | TFPL   | |
| TFP-L2RP  | GAIN NF     | JP2-LEFT  | 2-2            | TFPL   | |
| TFP-L2RA  | GAIN A      | JST3-LEFT | -              | TFPL   | |
| TFP-L2RB  | GAIN B      | JST3-LEFT | -              | TFPL   | |
| TFP-L2RC  | GAIN C      | JST3-LEFT | -              | TFPL   | |
| TFP-L3MP  | R/F UP      | JP3-LEFT  | 2-3            | TFPL   | |
| TFP-L4MP  | R/F DOWN    | JP3-LEFT  | 2-4            | TFPL   | |
| TFP-L5MP  | EL UP       | JP3-LEFT  | 2-5            | TFPL   | |
| TFP-L6MP  | EL DOWN     | JP3-LEFT  | 2-6            | TFPL   | |
| TFP-R1MP  | SYM UP      | JP4-RIGHT | 3-1            | TFPR   | |
| TFP-R2MP  | SYM DOWN    | JP4-RIGHT | 3-2            | TFPR   | |
| TFP-R3MP  | BRT UP      | JP4-RIGHT | 3-3            | TFPR   | |
| TFP-R4MP  | BRT DOWN    | JP4-RIGHT | 3-4            | TFPR   | |
| TFP-R5MP  | CON UP      | JP5-RIGHT | 3-5            | TFPR   | |
| TFP-R6MP  | CON DOWN    | JP5-RIGHT | 3-6            | TFPR   | |
| TFP-R7MP  | * DEFAULT   | JP5-RIGHT | 3-7            | TFPR   | |
| TFP-B1MP  | AZ LEFT     | JP6-BOT   | 4-1            | TFPB   | |
| TFP-B2MP  | AZ RIGHT    | JP6-BOT   | 4-2            | TFPB   | |
| TFP-B3MP  | MULTI B1    | JP6-BOT   | 4-3            | TFPB   | |
| TFP-B4MP  | MULTI B2    | JP7-BOT   | 4-4            | TFPB   | |
| TFP-B5MP  | MULTI B3    | JP7-BOT   | 4-5            | TFPB   | |
| TFP-B6MP  | MULTI B4    | JP7-BOT   | 4-6            | TFPB   | |
| TGL-01BMP | VIDEO REC   | | | | |
| TGL-02SMF | IAT EN/ACT  | | | | |
| TGL-02SMA | IAT OFS     | | | | |
| TGL-03HMF | TADS FOV Z  | | | | |
| TGL-03HMA | TADS FOV M  | | | | |
| TGL-03HML | TADS FOV N  | | | | |
| TGL-03HMR | TADS FOV W  | | | | |
| TGL-03HMP | TADS FOV NF | | | | |
| TGL-04SF  | SSEL FLIR   | | | | |
| TGL-04SC  | SSEL DTV    | | | | |
| TGL-04SA  | SSEL DVO NF | | | | |
| TGL-05HMF | FCR GTM     | | | | |
| TGL-05HMA | FCR ATM     | | | | |
| TGL-05HML | FCR TPM     | | | | |
| TGL-05HMR | FCR RMAP    | | | | |
| TGL-05HMP | FCR NF      | | | | |
| TGL-06JX  | CURSOR X    | | | | |
| TGL-06JY  | CURSOR Y    | | | | |
| TGL-06JP  | CURSOR ENT  | | | | |
| TGL-07HMF | WAS G       | | | | |
| TGL-07HMA | WAS A NF    | | | | |
| TGL-07HML | WAS R       | | | | |
| TGL-07HMR | WAS M       | | | | |
| TGL-07HMP | WAS NF      | | | | |
| TGL-08BMP | CURSOR L/R  | | | | |
| TGL-09SMF | POS STORE   | | | | |
| TGL-09SMA | POS UPD     | | | | |
| TGL-10BMP | WPN TRIG    | | | | |
| TGL-11SMF | FCR S-SCAN  | | | | |
| TGL-11SMA | FCR C-SCAN  | | | | |
| TGL-12BMP | CUED        | | | | |
| TGL-13BMP | CAGE NF     | | | | |
| TGL-14BMP | LMC         | | | | |

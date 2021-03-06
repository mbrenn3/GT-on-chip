#Cell-Cell attack and Gene Transfer
##Effects of CSP and cell density

###May 12 2016

###Cell cultures

**Attacker: CP2204** Rif-r Nov-s Sp-s. Stock 4/15/16. OD 0.2 BoxMorrison2016#1-20.

**Victim: Cp2215** Nov-r Sp-r. Stock 4/15/16 OD 0.2 BoxMorrison2016#21-40

Thaw Stock cells @ 0C. Dilute for growth in CDM + 1%CAT 12mL/tube.

Media batch CAT:4/8/16, CDM:5/9/16

To CAT from stock shelf add phosphate and glucose. For 300 mL CAT add 10 mL 0.5 M K2HPO4 (sterile filtered) and 3 mL 20% glucose (sterile filtered).

Grow to OD = 0.2 and chill to 0C for use.

| cells | Cp2204 | Cp2204 | Cp2204 | CP2215 | CP2215 | CP2215 |
|-------|--------|--------|--------|--------|--------|--------|
| vol   | 200 uL | 100 ul | 50 uL  | 200 uL | 100 uL | 50 uL  |
| tube  | A      | B      | C      | D      | E      | F      |
| 10:14 | 0.004  | 0.003  | 0.002  | 0.008  | 0.006  | 0.003  |
| 10:40 | 0.008  | 0.006  | 0.003  | 0.017  | 0.016  | 0.009  |
| 11:15 | 0.01   | 0.005  | 0.003  | 0.022  | 0.034  | 0.016  |
| 11:47 | 0.016  | 0.008  | 0.008  | 0.03   | 0.064  | 0.035  |
|       |        |        |        | RT     | RT     | RT     |
| 13:11 | 0.061  | 0.033  | 0.014  | 0.042  | 0.15   | 0.085  |
| 14:06 | 0.148  | 0.08   | 0.043  | 0.05   | 0.219  | 0.133  |
|       |        |        |        | 37C    |        | 37C    |
| 14:23 | 0.187  | 0.1    | 0.054  | 0.052  | 0.242  | 0.161  |
| 14:40 | 0.233  | 0.139  | 0.064  |        |        | 0.2    |
| 14:48 |        | 0.15   |        |        |        | 0C     |
| 14:56 |        | 0.162  |        |        |        |        |
| 15:02 |        | 0.184  |        |        |        |        |
| 15:08 |        | 0.195  |        |        |        |        |
|       |        | 0C     |        |        |        |        |

<img src="growth-curves.png" width="600" />

###Attack Reaction

Cell Prep:

At OD 0.2 chill to 0C.

Take 2 x 12 mL tubes of cell suspension and spin down at 8k RPM for 8 min in chilled incubator.

Pour off supernatant and resuspend in 0.75 mL chilled CDM resulting in OD 3.2

Combine cells suspensions to make 1.5 mL suspension, each strain at OD 1.6, hold at 0C.

Prepare reaction tubes according to following scheme. First add CDM to each tube followed by inducer and finally cells. Mix/votex tubes and gently centrifuge to bottom.

**Inducer Prep:**

| component | Stock     | Inducer   | Dilute by   | working stock | Vol/RX | Total (3.2x(Vol/RX)) |
|-----------|-----------|-----------|-------------|---------------|--------|----------------------|
| CSP       | 250 ug/mL | 0.1 ug/mL | 100         | 2.5 ug/mL     | 24 uL  | 76.8 uL              |
| BSA       | 4%        | 0.04%     | 10          | 0.4%          | 60 uL  | 192 uL               |
| CaCl2     | 1 M       | 5 mM      | 10          | 100 mM        | 30 uL   | 96 uL                |

*note: CaCl2 precipitated when diluted in CDM so it was diluted in sterile water instead*

**Reaction Scheme:**

| Reaction | OD of each strain | Vol. Cell Mix | Vol. Inducer | CDM   |
|----------|-------------------|---------------|--------------|-------|
| 1        | 1                 | 375           | 114          | 111   |
| 2        | 1                 | 375           | -            | 225   |
| 3        | 0.6               | 225           | 114          | 261   |
| 4        | 0.6               | 225           | -            | 375   |
| 5        | 0.3               | 112.5         | 114          | 373.5 |
| 6        | 0.3               | 112.5         | -            | 487.5 |

Put reaction tubes in heat block at 37C for 30 minutes. *reaction started at 3:42 PM*

After 30 min reaction, the 600 uL reaction mixture was diluted into 6 mL CAT and incubated at 37C for 60 minutes. *incubation starting at 4:18 PM*

**Expected Results**

|                          | Attacker | Victim    | single cross | single cross | double cross |
|--------------------------|----------|-----------|--------------|--------------|--------------|
| drug                     | Rif-r    | N-r, Sp-r | R-r, N-r     | R-r, Sp-r    | RNS          |
| expected number of cells | 10^9     | 10^9      | 10^5         | 10^5         | 30           |
| Dilution for plating     | 10^-5    | 10^-5     | 10^-2        | 10^-2        | 10^-1        |
| number of plates         | 1        | 1         | 2            | 2            | 3            |

**Dilution Scheme**

600 uL of reaction is diluted into 6 mL = 10^-1, 3 Plates: 3RNS

700 uL transfered into 7 mL = 10^-2, 4 plates: 2RN, 2RS

70 uL transfered into 7 mL = 10^-4, don't plate

600 uL transfered into 6 mL = 10^-5, 2 plates: 1R, 1S

Plates are filled with:

1. 3 mL CAT agar
2. 1.5 mL cells suspension mixed with 1.5 mL agar
3. 3 mL CAT agar
4. 3 mL Drug agar

**Drug Assay Prep**

| Drug | overlay  | Stock     |
|------|----------|-----------|
| R    | 40 ug/mL | 20 mg/mL  |
| N    | 10 ug/mL | 10 mg/mL  |
| S    | 160      | 100 mg/mL |

|     | total volume | R uL | N uL | S uL  |
|-----|--------------|------|------|-------|
| R   | 20 mL        | 40   | -    | -     |
| S   | 20 mL        | -    | 33.3 | -     |
| RN  | 40 mL        | 80   | -    | 133.3 |
| RS  | 40 mL        | 80   | 66.6 | -     |
| RNS | 60 mL        | 120  | 100  | 60    |

###Results

No transformaion was observed. The control for each strain, the R, and S treated plates did have cultures, plotted below.

<img src="results.png" width="600" />

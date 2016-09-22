#Cell-Cell attack and Gene Transfer
##Testing Transformation in M9 with Controls

###Sep 21 2016

###Cell cultures

**Attacker: CP2204** Rif-r Nov-s Sp-s. Stock 9/??/16. OD 0.2 BoxMorrison2016#1-20.

**Victim: Cp2215** Nov-r Sp-r. Stock 9/??/16 OD 0.2 BoxMorrison2016#21-40

Thaw Stock cells @ 0C. Dilute for growth in CDM + 1%CAT 12mL/tube.

Media batch CAT: COMB, CDM+CHO+G:9/12/16

To CAT from stock shelf add phosphate and glucose. For 300 mL CAT add 10 mL 0.5 M K2HPO4 (sterile filtered) and 3 mL 20% glucose (sterile filtered).

| cells | Cp2204 | Cp2204 |
|-------|--------|--------|
| vol   | 250 uL | 150 uL |
| tube  | A      | B      |
| 10:15 | 37C    | 37C    |
| 11:00 | 0.001  | 0.005  |
| 11:48 | 0.008  | 0.008  |
| 1:00  | 0.24   | 0.052  |
|       |        | RT     |
| 2:30  | 0.101  | 0.119  |

[comment]: <> (<img src="growth-curves.png" width="600" />)

###Attack Reaction

**Cell Prep:**

| Volume required per RX = | 500          |
|--------------------------|--------------|
| Inducer volume =         | 95           |
| OD required =            | 2            |
| Volume started =         | 12000        |
|                          |              |
| Grow to OD of:           | 0.1028806584 |
| Resuspend in:            | 500          |
| pippette into inducer:   | 405          |

Take 2 x 12 mL tubes of cell suspension and spin down at 8k rcf for 8 min in chilled incubator.

Resuspend and add to inducer

Load each strain in syringe

**Reaction Scheme:**
When cells meet in droplet device each will be at OD = 1

Droplet generation was done with an ice pack on the syringes.
The heated stage was used to monitor temperature which was about 28C
The outlet tubing fed into a reaction tube in a heat block on ice.
Droplets were generated for about 2.5 hours, and then the reaction tube was placed in a heat block at 37 C for 30 minutes.

*reaction started at:*

**Inducer Prep:**

| # reactions | 2     |       | total volume in reaction | 500       |                       |                  |
|-------------|-------|-------|--------------------------|-----------|-----------------------|------------------|
| Component   | Stock | unit  | Inducer                  | Dilute by | Working Stock         | incuder/reaction |
| CSP         | 250   | ug/mL | 0.2*                     | 50        | 5                     | 20               |
| BSA         | 4     | %     | 0.04                     | 10        | 0.4                   | 50               |
| CaCl2       | 1     | M     | 0.005                    | 10        | 0.1                   | 25               |
|             |       |       |                          |           | total volume inducer: | 95               |

**typically 0.1 ug/mL of CSP is used, it was doubled in this case to encourage transformation*

**Preparing Working Stocks:**

| Working Stocks | Stock  | M9   | dH2O |
|----------------|--------|------|------|
| CSP            | 25 uL  | 1 mL | -    |
| BSA            | 100 uL | 1 mL | -    |
| CaCl2          | 100 uL | -    | 1 mL |

**Emlusion Breaking**

After 30 min reaction 500 uL of CAT was pipetted into the tube and the whole volume was transfered to a 1.5 mL centrifuge tube.
 The tube was spun down in the mini centrifuge for 30 seconds.
The oil at the bottom of the tube was pipetted out leaving ~500 uL of suspension

 The volume was trandfered to a 2 mL open tube and filled to 2 mL with CAT.
 This tube was placed in a heat block at 37 C for 1 hour

**Dilution Scheme**

2 mL open tubes were used: 108 total tubes

150 uL from reacion tube pippetted into 4 1.5 mL tubes and incubated for 1 hr. = 10E-1 Plated RNS

150 uL was pipetted into 7 tubes of 1.5 mL = 10E-2 Plated RN and RS

15 uL pipetted into 1.5 mL = 10E-4 do not plate

15 uL pipetted into 1.5 mL = 10E-6 6 tubes plated with R and S

Plates are filled with:

1. 3 mL CAT agar
2. 1.5 mL cells + 1.5 mL agar
3. 3 mL CAT agar
4. 3 mL Drug agar

**Drug Assay Prep**

| Drug | overlay  | Stock     |
|------|----------|-----------|
| R    | 40 ug/mL | 20 mg/mL  |
| N    | 10 ug/mL | 10 mg/mL  |
| S    | 160      | 100 mg/mL |

| Agar | Total Plates | Volume Agar | R      | N     | S     |
|------|--------------|-------------|--------|-------|-------|
| R    | 15           | 55 mL       | 111 uL | -     | -     |
| S    | 15           | 55 mL       | -      | -     | 88 uL |
| RN   | 15           | 55 mL       | 111 uL | 55 uL | -     |
| RS   | 15           | 55 mL       | 111 uL | -     | 88 uL |
| RNS  | 15           | 55 mL       | 111 uL | 55 uL | 88 uL |

###Results

**Cell Counts Cells/mL**

| RX | Dilution | Colonies | squares | squares/plate | colonies/plate | Drug     | Cells/ml |
|----|----------|----------|---------|---------------|----------------|----------|----------|
| 1  | 1.00E-06 | 91       | 1       | 4             | 364            | R        | 2.43E+08 |
| 1  | 1.00E-06 | 82       | 1       | 4             | 328            | R        | 2.19E+08 |
| 1  | 1.00E-06 | 69       | 1       | 4             | 276            | R        | 1.84E+08 |
| 1  | 1.00E-06 | 52       | 3       | 100           | 1733.333333    | R-small  | 1.16E+09 |
| 1  | 1.00E-06 | 42       | 3       | 100           | 1400           | R-small  | 9.33E+08 |
| 1  | 1.00E-06 | 46       | 3       | 100           | 1533.333333    | R-small  | 1.02E+09 |
| 1  | 1.00E-06 | 88       | 1       | 4             | 352            | S        | 2.35E+08 |
| 1  | 1.00E-06 | 117      | 1       | 4             | 468            | S        | 3.12E+08 |
| 1  | 1.00E-06 | 102      | 1       | 4             | 408            | S        | 2.72E+08 |
| 1  | 1.00E-02 | 119      | 3       | 20            | 793.3333333    | RN       | 5.29E+04 |
| 1  | 1.00E-02 | 73       | 3       | 20            | 486.6666667    | RN       | 3.24E+04 |
| 1  | 1.00E-02 | 95       | 3       | 20            | 633.3333333    | RN       | 4.22E+04 |
| 1  | 1.00E-02 | 297      | 3       | 100           | 9900           | RN-small | 6.60E+05 |
| 1  | 1.00E-02 | 273      | 3       | 100           | 9100           | RN-small | 6.07E+05 |
| 1  | 1.00E-02 | 234      | 3       | 100           | 7800           | RN-small | 5.20E+05 |
| 1  | 1.00E-02 | 67       | 3       | 20            | 446.6666667    | RS       | 2.98E+04 |
| 1  | 1.00E-02 | 65       | 3       | 20            | 433.3333333    | RS       | 2.89E+04 |
| 1  | 1.00E-02 | 66       | 3       | 20            | 440            | RS       | 2.93E+04 |
| 1  | 1.00E-02 | 130      | 3       | 370           | 16033.33333    | RS-small | 1.07E+06 |
| 1  | 1.00E-02 | 169      | 3       | 370           | 20843.33333    | RS-small | 1.39E+06 |
| 1  | 1.00E-02 | 121      | 3       | 370           | 14923.33333    | RS-small | 9.95E+05 |
| 1  | 1.00E-01 |          |         |               | 16             | RNS      | 106.67   |
| 1  | 1.00E-01 |          |         |               | 7              | RNS      | 46.67    |
| 1  | 1.00E-01 |          |         |               | 6              | RNS      | 40.00    |
|    |          |          |         |               |                |          |          |
| 2  | 1.00E-06 | 68       | 1       | 4             | 272            | R        | 1.81E+08 |
| 2  | 1.00E-06 | 117      | 1       | 4             | 468            | R        | 3.12E+08 |
| 2  | 1.00E-06 | 80       | 1       | 4             | 320            | R        | 2.13E+08 |
| 2  | 1.00E-06 | 80       | 1       | 4             | 320            | S        | 2.13E+08 |
| 2  | 1.00E-06 | 77       | 1       | 4             | 308            | S        | 2.05E+08 |
| 2  | 1.00E-06 | 105      | 1       | 4             | 420            | S        | 2.80E+08 |
| 2  | 1.00E-02 | 77       | 3       | 20            | 513.3333333    | RN       | 3.42E+04 |
| 2  | 1.00E-02 | 77       | 3       | 20            | 513.3333333    | RN       | 3.42E+04 |
| 2  | 1.00E-02 | 77       | 3       | 29            | 744.3333333    | RN       | 4.96E+04 |
| 2  | 1.00E-02 | 69       | 3       | 370           | 8510           | RN-small | 5.67E+05 |
| 2  | 1.00E-02 | 79       | 3       | 370           | 9743.333333    | RN-small | 6.50E+05 |
| 2  | 1.00E-02 | 64       | 3       | 370           | 7893.333333    | RN-small | 5.26E+05 |
| 2  | 1.00E-02 | 57       | 3       | 20            | 513.3333333    | RS       | 3.42E+04 |
| 2  | 1.00E-02 | 54       | 3       | 20            | 380            | RS       | 2.53E+04 |
| 2  | 1.00E-02 | 56       | 3       | 20            | 360            | RS       | 2.40E+04 |
| 2  | 1.00E-02 | 121      | 3       | 370           | 14923.33333    | RS-small | 9.95E+05 |
| 2  | 1.00E-02 | 110      | 3       | 370           | 13566.66667    | RS-small | 9.04E+05 |
| 2  | 1.00E-02 | 133      | 3       | 370           | 16403.33333    | RS-small | 1.09E+06 |
| 2  | 1.00E-01 |          |         |               | 6              | RNS      | 4.00E+01 |
| 2  | 1.00E-01 |          |         |               | 3              | RNS      | 2.00E+01 |
| 2  | 1.00E-01 |          |         |               | 7              | RNS      | 4.67E+01 |
|    |          |          |         |               |                |          |          |
| 3  | 1.00E-06 | 123      | 3       | 40            | 1640           | R        | 1.09E+09 |
| 3  | 1.00E-06 | 117      | 3       | 40            | 1560           | R        | 1.04E+09 |
| 3  | 1.00E-06 | 130      | 1       | 40            | 5200           | R        | 3.47E+09 |
| 3  | 1.00E-06 | 69       | 1       | 4             | 276            | S        | 1.84E+08 |
| 3  | 1.00E-06 | 95       | 1       | 4             | 380            | S        | 2.53E+08 |
| 3  | 1.00E-06 | 65       | 1       | 4             | 260            | S        | 1.73E+08 |
| 3  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 3  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 3  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 3  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 3  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 3  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 3  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 3  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 3  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
|    |          |          |         |               |                |          |          |
| 4  | 1.00E-06 | 104      | 3       | 40            | 1386.666667    | R        | 9.24E+08 |
| 4  | 1.00E-06 | 94       | 3       | 40            | 1253.333333    | R        | 8.36E+08 |
| 4  | 1.00E-06 | 80       | 3       | 40            | 1066.666667    | R        | 7.11E+08 |
| 4  | 1.00E-06 | 67       | 1       | 4             | 268            | S        | 1.79E+08 |
| 4  | 1.00E-06 | 74       | 1       | 4             | 296            | S        | 1.97E+08 |
| 4  | 1.00E-06 | 97       | 1       | 4             | 388            | S        | 2.59E+08 |
| 4  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 4  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 4  | 1.00E-02 |          |         |               | 1              | RN       | 6.67E+01 |
| 4  | 1.00E-02 |          |         |               | 1              | RS       | 6.67E+01 |
| 4  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 4  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 4  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 4  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 4  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
|    |          |          |         |               |                |          |          |
| 5  | 1.00E-06 |          |         |               | 0              | R        | 0.00E+00 |
| 5  | 1.00E-06 |          |         |               | 0              | R        | 0.00E+00 |
| 5  | 1.00E-06 |          |         |               | 0              | R        | 0.00E+00 |
| 5  | 1.00E-06 | 87       | 1       | 4             | 348            | S        | 2.32E+08 |
| 5  | 1.00E-06 | 98       | 1       | 4             | 392            | S        | 2.61E+08 |
| 5  | 1.00E-06 | 77       | 1       | 4             | 308            | S        | 2.05E+08 |
| 5  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 5  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 5  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 5  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 5  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 5  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 5  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 5  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 5  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
|    |          |          |         |               |                |          |          |
| 6  | 1.00E-06 | 208      | 3       | 40            | 2773.333333    | R        | 1.85E+09 |
| 6  | 1.00E-06 | 219      | 3       | 40            | 2920           | R        | 1.95E+09 |
| 6  | 1.00E-06 | 181      | 3       | 40            | 2413.333333    | R        | 1.61E+09 |
| 6  | 1.00E-06 |          |         |               | 2              | S        | 1.33E+06 |
| 6  | 1.00E-06 |          |         |               | 0              | S        | 0.00E+00 |
| 6  | 1.00E-06 |          |         |               | 0              | S        | 0.00E+00 |
| 6  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 6  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 6  | 1.00E-02 |          |         |               | 0              | RN       | 0.00E+00 |
| 6  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 6  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 6  | 1.00E-02 |          |         |               | 0              | RS       | 0.00E+00 |
| 6  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 6  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |
| 6  | 1.00E-01 |          |         |               | 0              | RNS      | 0.00E+00 |

**Summary of Results by cell count (cells/mL)**

| Reaction | CDM | Inducer (CSP) | Cells  | Rifampicin (R) | R-Small  | Spectinomycin (S) | RN       | RN-small | RS       | RS-small | RNS         |
|----------|-----|---------------|--------|----------------|----------|-------------------|----------|----------|----------|----------|-------------|
| 1        | 20% | +             | Mix    | 2.15E+08       | 1.04E+09 | 2.73E+08          | 4.25E+04 | 5.96E+05 | 2.93E+04 | 1.15E+06 | 64.44444444 |
| 2        | 0%  | +             | Mix    | 2.36E+08       | -        | 2.33E+08          | 3.94E+04 | 5.81E+05 | 2.79E+04 | 9.98E+05 | 35.55555556 |
| 3        | 20% | -             | Mix    | 1.87E+09       | -        | 2.04E+08          | 0        | -        | 0        | -        | 0           |
| 4        | 0%  | -             | Mix    | 8.24E+08       | -        | 2.12E+08          | 0        | -        | 0        | -        | 0           |
| 5        | 20% | +             | CP2204 | 0              | -        | 2.33E+08          | 0        | -        | 0        | -        | 0           |
| 6        | 20% | +             | CP2215 | 1.80E+09       | -        | 0                 | 0        | -        | 0        | -        | 0           |

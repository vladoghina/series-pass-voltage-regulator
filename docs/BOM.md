# Bill of Materials: Series-Pass Voltage Regulator

All passives: SMD chip 0805, ±5%, 0.125 W. Semiconductors: SMD catalogue parts.

## Semiconductors

| Reference | Part | Package | Function |
|---|---|---|---|
| Q1, Q2, Q3, Q4, Q9, Q10 | BC846B (NPN) | SOT-23 | Current mirror (Q1, Q2), differential pair (Q3, Q4), thermal protection (Q9), overcurrent protection (Q10) |
| Q5, Q6, Q7, Q12 | BC856B (PNP) | SOT-23 | Active load of the error amplifier (Q5, Q6), current mirror (Q7, Q12) |
| Q8 | BC817-25 (NPN) | SOT-23 | Driver of the Darlington pair |
| Q11 | MJD31C (NPN, power) | D-PAK | Series-pass transistor |
| D2 | BZX84C5V1 (Zener, 5.1 V) | SOT-23 | Voltage reference |
| D5, D6 | SMD LED, 0805 (OF-SMD2012B, blue) | 0805 | Input / output indicators (1N4148 used in the PSpice model) |

## Resistors and potentiometer

| Reference | Value | Qty | Function |
|---|---|---|---|
| R3, R5, R6, R7, R8 | 100 Ω | 5 | Emitter degeneration / mirror loads |
| R10 | 33 Ω | 1 | Emitter degeneration (PNP mirror) |
| R28 | 2.7 kΩ | 1 | Current reference branch |
| R29 | 3.3 kΩ | 1 | Current reference branch |
| R26 | 680 Ω | 1 | Zener series resistor |
| R11, R21 | 3.3 kΩ | 2 | Feedback divider |
| R15 | 5 kΩ SMD potentiometer (3314G-1-502E) | 1 | Output voltage adjustment |
| R16, R17, R18, R19, R20, R42 | 1 Ω | 6 | Current sensing (overcurrent protection) |
| R23 | 220 Ω | 1 | Thermal protection divider |
| R24, R25 | 1.8 kΩ | 2 | Thermal protection divider |
| R9 | 470 Ω | 1 | Thermal protection divider |
| R30-R34 | 510 Ω | 5 | Input LED current limiting (series) |
| R43-R45 | 470 Ω | 3 | Output LED current limiting (series) |
| R37-R41 | 150 Ω | 5 | Nominal load, 750 Ω in total (series) |

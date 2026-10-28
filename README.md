# Linear-Regulator-Practice-PCB
Beginner 2-layer PCB project with kiCAD. This board contains three 78xx linear regulators. 
<img width="4032" height="2268" alt="pic" src="https://github.com/user-attachments/assets/10c716e4-a36f-475f-a3cf-af2e14a639cd" />


Schematic:
<img width="1526" height="365" alt="schematic" src="https://github.com/user-attachments/assets/76738882-4ae5-4d07-84bd-3c583eaacb49" />

PCB Layout and render.
<img width="1819" height="845" alt="pcb and render" src="https://github.com/user-attachments/assets/4b76372a-3de9-4930-be8e-19d830739755" />

BoM
| Reference         | Qty | Value                    | Footprint                                                    | DigiKey P/N      |
|-------------------|-----|--------------------------|--------------------------------------------------------------|------------------|
| C1,C3,C5          | 3   | 0.22uF 50V CER           | Capacitor_SMD:C_1206_3216Metric                              | 445-2283-1-ND    |
| C2,C4,C6          | 3   | 0.1uF 50V                | Capacitor_SMD:C_1206_3216Metric                              | 1276-1068-1-ND   |
| D4                | 1   | D                        | Diode_SMD:D_SMC_Handsoldering                                | S5AC-FDICT-ND    |
| J1,J2,J4,J5       | 4   | Screw_Terminal_2_P3.50mm | TerminalBlock_Phoenix_PT-1,5-2-3.5-H_1x02_P3.50mm_Horizontal | 732-2747-ND      |
| R1,R2,R3,R4,R5,R6 | 6   | 330                      | Resistor_SMD:R_1206_3216Metric                               | 311-330FRCT-ND   |
| U1                | 1   | L7805                    | Package_TO_SOT_SMD:TO-252-2                                  | 497-7255-1-ND    |
| U2                | 1   | L7809                    | Package_TO_SOT_SMD:TO-252-2                                  | BA7809FP-E2CT-ND |
| U5                | 1   | L7812                    | Package_TO_SOT_SMD:TO-263-3_TabPin2                          | 296-44522-1-ND   |


# Flip-Flop Circuit with N555 Timer
Double Sided PCB design of Flip-Flop circuitwith NE555 Timer using KiCad.
Dimensions 25 mm x 27 mm.

## Schematic of circuit
![flip-flop-schematic-](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/96e8f9cd-2b9d-4d49-b6f5-939b52184fb5)
### ERC Result:
![erc](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/71ea6938-224a-4d0e-b644-39850aeb1634)

## PCB Board
FRont Copper:
![flip-flop-pcb-front-copper](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/e3f098f6-4d0f-4e10-a1e7-2b64310d2300)
### Back Copper:
![flip-flop-pcb-back-copper](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/691adbd1-fe27-44ed-ab3d-5c40aecdef75)
### Silkscreen:
![flip-flop-pcb-back-silkscreen](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/71cf91a1-50c7-49d0-93fc-eb8fb18d2438)
### DRC Result:
![drc](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/3de538df-642d-449e-9d75-ad2d362a8994)

## 3D view of PCB
### Front:
![flip-flop-NE555-timer-3d-front](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/0ff980fd-7ae0-4257-9254-95036e5e3a31)
### Back:
![flip-flop-NE555-timer-3d-back](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/2ec0441a-f6ef-443b-8a34-5b3b473042bd)

# Gerber
### Front Copper:
![flip-flop-gerber-front-copper](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/6f341eb8-a536-4b09-9f25-2c76ecf7235b)
### Back Copper:
![flip-flop-gerber-back-copper](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/2031093d-22c1-402d-b373-9382672f65d8)

## BOM
| Id  | Designator | Footprint | Quantity | Designation | Supplier and ref |
| --- | --- | --- | --- | --- | --- |
| 1   | R3  | R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal | 1   | 100k |     |
| 2   | R4  | R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal | 1   | 50k |     |
| 3   | D1,D2 | LED_D3.0mm | 2   | LED |     |
| 4   | U1  | DIP-8_W7.62mm_LongPads | 1   | NE555P |     |
| 5   | R2,R1 | R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal | 2   | 330 |     |
| 6   | C2  | CP_Radial_D6.3mm_P2.50mm | 1   | 10u |     |
| 7   | C3  | C_Disc_D3.0mm_W1.6mm_P2.50mm | 1   | 0.1u |     |
| 8   | J2  | Molex_KK-254_AE-6410-02A_1x02\P2.54mm_Vertical | 1   | Conn\_01x02\_Pin |     |

# REFERENCES
[1]  https://www.udemy.com/course/kicad-ile-pcb-tasarimi-elektronik-kart-tasarimi/

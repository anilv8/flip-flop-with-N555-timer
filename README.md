# Flip-Flop Circuit with N555 Timer
Double Sided PCB design of Flip-Flop circuitwith NE555 Timer using KiCad.
Dimensions 25 mm x 27 mm.
## Schematic of circuit
![schematic](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/1efa9a7e-7499-43bb-b09a-656a1879d53d)
### ERC Result:
![erc](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/71ea6938-224a-4d0e-b644-39850aeb1634)
## PCB Board
![pcb](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/1247d692-48f2-4463-82e6-25adac8de5a0)
### DRC Result:
![drc](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/3de538df-642d-449e-9d75-ad2d362a8994)
## 3D view of PCB
### Front:
![pcb-3d-front](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/3f695e45-1f27-4161-8cef-2636062d09fc)
### Back:
![pcb-3d-back](https://github.com/anilv8/flip-flop-with-N555-timer/assets/81171588/a2050e7b-1a48-4ef2-bc0d-78a41a23d095)

# BOM
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

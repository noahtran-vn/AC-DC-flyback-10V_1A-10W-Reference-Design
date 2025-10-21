# AC-DC-flyback-10V_1A-10W-Reference-Design
### Version: 1.0
**This repository contains the complete design file for a 10W, 10V/1A isolated flyback converter.**


This reference design serves a solid starting point for engineers, students, and hobbyists looking for develop their own custom Switched-Mode Power Supplies (SMPS).
## ⚡️ Key Specifications
| Parameter | Value | Notes |
|:---:|:---:|:---:|
| Input Voltage Range |85VAC - 264VAC| Universal Input |
| Output Voltage | 10 VDC    |  |
| Output Current | 1 A (Max) |  |
| Output Power   | 10W       |  |
| Regulation Method |	Primary-Side Regulation (PSR) |	No Optocoupler required |
| Efficiency |	> 80% at full load | |
| Protections	| Over-Current, Short-Circuit, Over-Voltage	| Integrated into the controller IC |
## ⚙️ Hardware & Components
This design is based on common and high-performance components:

- Controller IC: KP21824M (or equivalent PSR controller), intergrated internal MOSFET.

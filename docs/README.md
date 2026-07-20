# Honey-hub
This repository contains komplete plans for produktion and assembly of PCB of Honey Hub. This project was designed in easy eda pro and autodesk fusion.

## Technical specifications
Power supply: 5V by USB-C 
Connectors: USB-C (Type-C-16pin), USB-A
Chip: U1 by corechips

## Production and assembly
This project is optimalized for production and assembly by JLCPCB, because of already assigned LCSC codes.

## How to open project
1. Go on Easy Eda Pro
2. Login to your account
3. Import project or open file '.epro'

## Why?
Since my laptop has only 2 USB-A ports and 1 USB-C I often don't have enough space to plug in all my peripherals.


## Assembly Instructions
1. Gather all required parts: the PCB, 3D‑printed enclosure pieces, screws, cables, and basic tools.

2. Inspect the PCB for any solder bridges, bent pins, or loose connectors.

3. Plug the PCB into your laptop to verify it powers on and all ports work correctly.

4. Place the PCB into the bottom half of the 3D‑printed enclosure and check that all USB ports align with the openings.

5. Secure the PCB using screws, standoffs, or a small piece of double‑sided tape to keep it stable.

6. Position the top part of the enclosure and make sure it doesn’t press against any components.

7. Close or screw the enclosure together so everything fits tightly.

8. Connect the USB cable and test all ports again under normal use.

9. Confirm there is no overheating, disconnecting, or mechanical stress on the connectors.

10. Add labels or simple cable management if you want a cleaner setup.

## BOM
1. 3 USB-C connectors
2. 2 USB-A connectors
3. m2 screaws
4. 3d printed case
5. capacitors, resistors
6. pcb

## Licence
This project is licenced by NC. More info is in file LICENCE.

## Schematics
I designed the entire schematic in EasyEDA Pro, because it provides fast LCSC parts assignment. I focused to ensure the schematic is clean, safe and easy to read:
- correct integration of USB-C and USB-A connectors
- input safety
- clean and readable signal layout
- minimalizing crossing routes
<img width="2320" height="1635" alt="SCH_New Project_1-Sheet_1_2026-07-18" src="https://github.com/user-attachments/assets/fc411f79-83f3-4b6e-8e12-60c8ecf69465" />

## PCB Design
I also designed the PCB in EasyEDA Pro, keeping simple layout with JLCPCB standarts
- It's 2 layer board
- All vias and trace widths follow JLCPCB manufacturing standards
- The power filtering is placed near the input to minimize noise
<img width="753" height="572" alt="Snímek obrazovky 2026-07-18 094726" src="https://github.com/user-attachments/assets/5b3fa664-76a1-474c-b20f-2d1c57bf93df" />
<img width="780" height="563" alt="Snímek obrazovky 2026-07-18 094743" src="https://github.com/user-attachments/assets/b60487b3-4fca-498b-bfbb-72ef5af135ab" />
<img width="874" height="577" alt="Snímek obrazovky 2026-06-11 164115" src="https://github.com/user-attachments/assets/e3306612-995f-4f7a-97cd-7bb46d751b65" />
<img width="412" height="203" alt="Snímek obrazovky 2026-06-22 212639" src="https://github.com/user-attachments/assets/faa7c357-17b1-4fe4-a333-5d2daf06be66" />
<img width="395" height="332" alt="Snímek obrazovky 2026-06-26 203202" src="https://github.com/user-attachments/assets/4b0ecded-b582-4b2e-b394-6206025723e9" />
<img width="1748" height="2480" alt="Hack hub 4 zine" src="https://github.com/user-attachments/assets/58e73d93-3180-4f2f-a942-82a45c127184" />




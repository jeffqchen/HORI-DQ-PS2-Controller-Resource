# Controller Cable Adapter

<img src="https://github.com/user-attachments/assets/92955c8c-7eef-47fa-b764-a5fc952b4f53" width=800 />

<img src="https://github.com/user-attachments/assets/c210947a-22c4-49bc-8f80-fabfa517f91f" width=400> <img src="https://github.com/user-attachments/assets/46f5cce8-cf74-4d3c-b806-e82ae4b686d4" width=400>

This controller has a non-standard Mini DIN 8 pin connector. To connect to the PS2, you must use the enclosed cable. Without the cable, this controller is unusable.

This adapter follows the asthetics of the official controller plug, and does not intefere with the memory card.

<img src="https://github.com/user-attachments/assets/6f6a02c5-e47d-45b4-a7b3-8114aa7a72f6" width=400> <img src="https://github.com/user-attachments/assets/942c313c-af84-40a0-b7e1-3df9c1d5482f" width=400>

## Parts

- PCB: [Gerber File](./PCB/gerber/DQ%20PS2%20Controller%20Adapter.zip)
- 8 pin Mini DIN Female Recepticle, Through Hole - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Connectors/Mini%20DIN/Female/8%20Pin/info.md)
- PlayStation Controller Plug, Male Pins, Right Angle - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Connectors/PlayStation%20Controller%20Port/Male%20Plug/info.md)
- 3D Printed Shell: [STL Files](./Shell)
- M2x20mm screw and hex nut - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Parts/M2%20M3%20Hex%20Screw%20%26%20Nut/info.md)
- 8 pin Mini DIN Cable, Male, Straight - [Link](https://github.com/jeffqchen/JeffParts/blob/main/Cable/Mini%20DIN/8%20Pin/Male/Straight/info.md)

## Assembly

### PCB

<img src="https://github.com/user-attachments/assets/08f1eae3-9320-4632-9b6b-ff90ee0133c7" width=800 />

Pay attention the silkscreen when populating the connector.

Make sure the PlayStation Plug is soldered as inward as possible, as shown in the picture.

### Shell

First, push the PlayStation plug through from the inside of the inner shell. There will be resistence, since there are hooks designed to prevent the plug from backing out.

Then, close the outer shell onto the assembly. Make sure there is no gap between the shell.

Lastly, thread the M2 screws from the outer shell into the inner shell, then tighten it down with the nuts on the other side.

## Misc

This controller used the outer shielding of the Mini DIN cable as the GROUND for the rumble motors. If your cable did not connec that, there will be no rumble effects.

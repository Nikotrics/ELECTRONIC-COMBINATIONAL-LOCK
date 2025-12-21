# ELECTRONIC COMBINATIONAL LOCK (WITHOUT ARDUINO)

## Description
This project is an **electronic combinational lock** built **without using a microcontroller**.  
It uses **logic ICs (4030 and 4001)** to implement a fixed password-based locking system.

## How It Works
- A predefined combination is set using logic gates.  
- When the correct input combination is entered, the logic output becomes HIGH.  
- This output activates the lock (LED / relay / buzzer).  
- Any incorrect combination keeps the lock in the locked state.

## ICs Used
- **CD4030** – XOR Gate IC  
- **CD4001** – NOR Gate IC  

## Components
- CD4030 IC  (1)
- CD4001 IC  (1)
- TIP 122    (1)
- LM7806 (12V to 5V)  (1) 
- Push button  (1)
- Two way switches (4 + 4)  
- Resistors 10K, 2.2K, 470 Ohm (10 + 1 + 72) 
- LEDs / Buzzer / Lock  (2 + 1 + 1)
- DC power supply (1 + 1)
- 7-Segment CC (4 + 4 + 4)
- 1N914 (4)
- Diode (1)
- Breadboard (1 + 1)
- On/Off Switch (1)
- Jumper Wire M to M, F to M (80 + 80)
- Soldering wire 

## Applications
- Electronic door locks  
- Security systems  
- Password-based access control  
- Learning digital logic design

## Possible Combinations
2^n
n = 4
2^4 = 16

1. 0000
2. 0001
3. 0010
4. 0011
5. 0100
6. 0101
7. 0110
8. 0111
9. 1000
10. 1001
11. 1010
12. 1011
13. 1100
14. 1101
15. 1110
16. 1111

## Circuit / Images
- Circuit diagram and breadboard image in folder  
- Demo Video in folder

## Folder Structure
1. Proteus
2. Software
3. Hardware
4. Video

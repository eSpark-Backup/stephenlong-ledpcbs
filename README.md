# Direct Drive and Full Circuit LED Proto PCBAs
#### Client Name: Stephen Long Jr.

## Project Requirements
Refer to 2x2 design pushed in docs folder and carry out below requirements (the 2x2 design probably references more to the Full Circuit LED Proto PCBA)

### Full Circuit LED Proto PCBA
- Spaced 10mm center to center.
- Arranged in a 2 wide, 3 high grid.  
![image](https://github.com/user-attachments/assets/ed9583c2-736e-4447-8317-5230c0193d39)
- UCS 7604 constant-current driver IC
- Required resistors, capacitors, and other supporting circuitry.
- Voltage VDD, GND, and data input/output lines will terminate in accessible solder pads for easy interfacing.
- The board should allow user to have both direct drive and full circuit capabilities by the following approach:
    - run each positive and negative pad to a row of jumpers, each LED will have 3 pins on this jumper header assigned to it. The center pin will be connected to the trace for the LED pad. The left pin will be connected to the full driving circuit with IC. The right pin will go directly to a solder pad. This sequence will happen for each led (x12), then:
        - **For Direct Drive:** User would put all the jumpers over to the center and right pin, then solder wires to the solder pads.
        - **For Full Circuit:** User would put all of the jumpers on the left and center pin for each LED.
- 4 x mounting holes for M3 screw clearance.

## Battery tester
Battery tester for AA, AAA, LR44, CR2032 batteries.

### Description
Each battery size is tested at approximately 15% of its rated capacity.
R5 acts as a voltage divider by 2 and should be equal to sum of R2, R3, R4.

### BOM
- R1 - small potentiometer
- R2, R3, R4, R5 - 0.25 W resistors
- MES1 - 0.2 mA analog measuring head
- Nickel plated strip 10х0.1 mm

### Assembly
Case:
 - Print the case using provided project file
 - Prepare our own file using PrusaSlicer or similar software. Cut the case horizontally in half at 5mm from the plate, add connectors.
Consider adding fuzzy skin on outer panels manually.

Prepare nickel plated strips by cutting them into needed sizes. Use hot soldering iron (300C) to put them in place.
 
Install measuring head. 

Solder resistors according to the provided schematic.

Use R1 to set MES1 to the value corresponding to a fresh new battery.

Photo of assembled device
![Photo of the battery tester](https://github.com/volodymyrburdeinyi/battery-tester/blob/default/photo.jpg)

# sprydrive

SpryDrive is an affordable actuator based on the quasi-direct drive (QDD) scheme. It is composed of a brushless outrunner motor, a low-cost metal gearbox, and a 3D-printed housing. Inspired by Gabrael Levine's OpenTorque actuator, but takes up less volume.

Output Backlash: ~0.13 degree  
Gear Ratio: 7:1  
Motor: Herlea X8318S or Turnigy 9235

The 8318 motor and 9235 motor are nearly identical, but the 8318 is 2.5 mm longer, so there are two versions of the design. Keep this in mind when ordering parts.

## Instructions

### Useful Tools

1. Hex key set
2. Arbor press
3. Milling machine with end mill (Don't worry, this is for a very easy, simple facing operation).
4. 400 grit sandpaper
5. Electric drill
6. M4 tap
7. Glue stick
8. A 3D printer and nylon, ABS, or PLA filament. I recommend Prusa.
9. Micrometer

### Steps

*Pictures coming soon!*

1. See SpryDrive BoM.xlsx for part sourcing. Order from McMaster if you're in a rush, order Aliexpress if you want to save money. Same thing with HobbyKing versus Alibaba/Aliexpress.

2. Submit LaserCut.DXF to SendCutSend.com for the aluminum Adapter Plate and Output Mounting Plate. Choose Aluminum 6061 (Not 5052) and a thickness of 0.125". I have included 6 copies of each component in the DXF because $29 is their minimum charge. If you want more, the best way to change this is to install something like [QCAD](https://qcad.org/en/) and duplicate outlines as needed.

4. Use an arbor press or vise to press out the dowel pins that come with the VersaPlanetary carrier plate. You will need a small piece of hardware to push directly on the pins, such as a smaller dowel pin. (Pictures coming soon).

5. The M4x18 dowel pins will replace the ones you just removed. You will need to sand the diameter down to achieve a proper press fit with the carrier plate. Mark off a 10 mm section of one end for sanding.

6. Insert the other end into an electric drill and hold a 400 grit sandpaper sheet around the 10 mm section while spinning the dowel pin at high speed. Measure the diameter with a micrometer every 30 seconds or so. The pin will start out at about 4.003 mm (.1576 in), and you want it to measure about 3.978 mm (.1566 in). This can take a few minutes. You wouldn't think taking off one thou would matter, but it means the difference betweeen a broken carrier plate and an easy press fit. I learned this the hard way!

7. Use an arbor press to insert the dowel pin into the VersaPlanetary carrier plate. The dowel pin should extend out 8 mm on one side and 5.3 mm on the other.

8. Repeat steps 5-7 for the other two dowel pins.

9. Tap the 3.5 mm holes in the laser cut Output Mounting Plate with an M4 tap.

10. Using an end mill, face the ring gear down by roughly 3.2±0.5 mm. Be sure to fixture this carefully, you don't want to deform it. The purpose of this operation is just to reduce the length of the actuator. If you want to skip this step, you can simply increase the length of the 3D-printed frame by 3.2 mm, but the sun gear will have less contact area with the planets.

11. 3D-print the Frame, Output Plate, Back Plate, Bearing Cover, Magnet Holder, and Encoder Mount. I used PLA, but you can use nylon, ABS, PETG, etc. Use 50% infill and at *least* 4 perimeters.

12. When printing the Output Plate, you must stop the print partway through to insert the bearing. It depends on your printer, but here is one [guide](https://www.youtube.com/watch?v=MfUjkI0ugX8). I recommend using a glue stick to help the rest of the print adhere to the bearing face.

13. Use a soldering iron to insert the heat-set inserts into the Frame.

14. Press the ring gear into the Frame.

15. Press the sun gear into the Adapter Plate. You may need an arbor press for this.

15. The rest of the assembly is easy and can be done using the assembly model as reference.

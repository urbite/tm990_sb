# TM990 Mechanicals

Thanks to Scott Baker for providing STL files for 3D-printable brackets. There are 5 different brackets needed to secure the backplane (Stuart Connor's reproduction, in this case).
1. 4-slot card guide, side 2 bottom - **tm990-case-bracket.stl**
2. 4-slot card guide, side 1 top - **tm990-case-extension.stl**
3. 4-slot card guide, side 1 bottom - **tm990-case-bracket-far.stl**
4. 4-slot card guide, side 2 top - **tm990-case-extension-far.stl**
5. Backplane hold-down brackets - **tm990-case-clip.stl**

## Assembly
### 4-slot card guide
Each 4-slot card guide consists of two pieces. These are designed to be assembled using threaded inserts that are installed using a soldering iron with a special tipe. Push the inserts into the 3D piece until the end is flush with the surface of the printed piece. Then assemble the pieces. IIRC, the holes are designe for 3mm machine screws.
Installing the threaded inserts was not a straightforward process.
- The iron should not be overly hot or the insert will be loosely fitted and difficult to get oriented correctly
- The iron needs to be perpendicular to the surface of the printed piece
- The insert needs to be pressed in the correct amount
For reliable heat insert installation, the decision was made to purchase a jig with an iron with settable temperature. The temperature is set to match the print material used. Also included were the tips for various size screw diameters, and a spring loaded stand with adjustable stop. This allows the insert to be installed perpendicular to the material, while the stop allows setting an exact depth.

For this configuration, threaded standoffs were used, with male on the upper side and female on the lower side. The assembled side 1/side 2 card guides were placed on the backplane, then the threaded standoffs were screwed into the threaded inserts by running the standoff screw through the bottom of the backplane PCB holes (that I drilled) in the backplane.

### Backplane holddown brackets
The backplane+card guide assembly is mounted on an 1/8 plexiglass sheet, using the case clips. The thicker part of the clip, between the backplane slot and edge faces downward to give the most clearance between the backplane connector pins and the plexiglass.
Holes were drilled into the plexiglass so there were roughly equally spaced and didn't interfere with the termination resistors on one side of the board. Heated threaded inserts were pressed into the plexiglass. After installing the plexiglass inserts and doing some research, I wouldn't recommend doing this. Instead I would recommend running a long screw between the top of the holddown bracket and standoff on the bottom of the plexiglass - much easier.

Here are some pics of the finished assembly.

[TM990_backplane + mechanicals](./TM990_backplane+mechanicals-crop1.png)  
[TM990_backplane + TM990/100MA + TM990/311](TM990_100MA+311-crop1.png)
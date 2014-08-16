A battery dispenser, and an extension to increase number of batteries held modelled in FreeCAD for 3D printing.

To get the two files to produce a model of the correct size, both need to have the dimensions entered.

| Battery Size | Diameter              | Length                | Extension Length | Overall Length |
| ------------ | --------------------- | --------------------- | ---------------- | -------------- |
| AAA          | 12 (10.5 + clearance) | 46 (44.5 + clearance) | 60               | 100            |
| AA           | 16 (14.5 + clearance) | 52 (50.5 + clearance) | 60               | 100            |
| 18650        | 20 (18 + clearance)   | 72 (70 ~~65.0~~ + clearance) | 60        | 100            |

Note: The 18650 is longer than the 65mm the size specifies, as protected 18650 batteries are longer due to the protection board.

# Bugs
* sometimes, the fillet steps stops working, and need to be reapplied.
 * for the extension, all external edges, apart from those on the locating tab
 * for the base, a 5mm fillet to take off the sharp corners on the top of the tabs holding the batteries in place

KobraMe
-------

This is my adapter for mounting the Hero Me Gen6 to the Anycubic Kobra. The files are in [FreeCAD](https://www.freecad.org/) format, assembled with the [Assembly4](https://wiki.freecad.org/Assembly4_Workbench) workbench and using parts from the [Fasteners Workbench](https://wiki.freecad.org/Fasteners_Workbench).

Here's the adapter just screwed in to the Kobra's carriage:

![A plastic rectangular teal block sits in a 3D printer toolhead carriage. It has the text 'KobraMe 6' scrawled on it in marker. The block has two large holes for the carriage's back hole, two heat set screw holes for the toolhead PCB on the left, and four raised holes for the Hero Me base on the right.](adapter1.jpg)

Here's the toolhead PCB and Hero Me screwed on to the adapter.

![A standard Hero Me adapter made out of a mix of dark blue and teal plastic hangs in the air. The wires from its components connect to a toolhead PCB to its left. Both are mounted against a hidden toolhead adapter. A set of teal cat ears sit on top of the extruder.](adapter2.jpg)

Usage guide
-----------

You will need:

- 1x A Hero Me Gen6
- 6x M3 heat sets
- 4x M3 8mm screws (optional, the Kobra toolhead screws will work)

Printing guide:

1. Load one of the PRINT_ME files in to your slicer
1. Slice as usual, no supports are needed
1. Print the adapter
1. Insert heat sets in to the sides and PCB holes
1. Remove sacrifical plastic from the base holes

Assembly guide:

1. Unplug, remove and disassemble the Kobra's toolhead
1. Disconnect and remove the toolhead PCB from the Kobra's toolhead
1. Screw the toolhead PCB into the adapter
1. Screw the Hero Me base into the adapter
1. Hold and line up the assembled adapter up with the carriage's holes
1. Partially screw in the top right screw
1. Partially screw in the bottom left screw
1. Partially screw in the other two screws
1. Fully screw in all screws
1. Connect the PCB adapter

Modification guide:

1. Install FreeCAD
2. Open ```Adapter.FCstd```
3. Make your desired modifications 
4. Click on the EXPORT_ME object
5. Open the File menu and click Export

Extras
------

Running the Hero Me on your printer will require custom firmware. The easiest way to do this is using Klipper. Unfortunately mainline Klipper does not work on the Kobra.

I work on and recommend [Catboat](https://github.com/printers-for-people/catboat), a fork of Klipper that works on the printer without any hardware modification.

I also recommend putting Koz's [Moons motor cat ears](https://www.printables.com/model/430159-moons-motor-cat-ears) on your printer. Nyan!

Hero Me License
---------------

The HeroMe.FCStd contains contains content from the [Hero Me Gen6](https://www.printables.com/model/308109-hero-me-gen6-archive) project.

Hero Me Gen6 is copyright 2022 Andrew Soderberg, released under the [CC BY-NC-SA 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/) license. A copy of this license can be found in the ```CC-BY-NC-SA-4.0.txt``` file.

This project modifies this content to create a FreeCAD assembly for measurements. These modifications are also licensed under the CC BY-NC-SA and are copyright 2023 Jookia.

KobraMe License
---------------

Excluding HeroMe.FCStd, KobraMe is copyright 2024 [Jookia](mailto:contact@jookia.org) and released under the [CC BY-SA 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license. A copy of this license can be found in the ```CC-BY-SA-4.0.txt``` file.

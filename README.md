# Working set for using SKR mini e3 board on Kingroon KP3

## Folders
* Marlin_SKR_E3_v12_KP3 : Marlin for SKR Board
* Mount : STL, FreeCAD files
    * board_spacer - SKR board mount on KP3
    * display - Display mount for `Zonestar OLED Display`

## Marlin bugfix 2.0.x - WIP. Please do not use it
* Marlin code from BIQU github and I fix a bug which not working save.

## Mount
* I used freecad for design board mount.
* Not tested yet. You may should check and edit dimension.

## Parts you should prepare
* Micro sd extension adapter
* USB mini-b extension cable
* Dupont jumper cable (male-female) - ~~~3pin (MKS Robin) to 2pin (SKR mini) for fans connection on KP3~~~
    * JST XH2.5 crimp tool - https://www.amazon.com/IWISS-Terminal-Crimping-SN-01BM-0-08-0-5mm/dp/B019ARWWFY
* Display - ~~~OLED 0.96`, Rotary Switch, Speaker~~~
    * Zonestar OLED Display - https://aliexpress.com/item/4000839370779.html

## Todo
* [ ] ~~~Schematic, Pin map for display~~~
* [V] Mount model for display
* [ ] Marlin configuragtion for Zonestar LCD using
# Working set for using SKR mini e3 board on Kingroon KP3
## WIP

## Folders
* Marlin_SKR_E3_v12_KP3 : Marlin for SKR Board
* Mount : STL, FreeCAD files
    * board_spacer - SKR board mount on KP3
    * board_spacer2 - Turned place of skr board 90 degree clock wise
        * Should remove 1 of stock mounting screw on floor of kp3 which hit skr board
    * display - Display mount for `Zonestar OLED Display`
        * Because rotary encoder handling is hard, made possible to place encoder at left side by turn 180 degree the display board

## Marlin bugfix 2.0.x - WIP. Please do not use it
* Marlin code from BIQU github and I fix a bug which not working save.

## Mount
* I used freecad for design board mount.
* Not tested yet. You may should check and edit dimension.

## Parts you should prepare
* Micro sd extension adapter
* USB mini-b extension cable
* JST XH2.5 Connector - `3pin (Stock MKS board)` to `2pin (SKR)` for fans connection on KP3
    * Crimp tool - https://www.amazon.com/IWISS-Terminal-Crimping-SN-01BM-0-08-0-5mm/dp/B019ARWWFY
    * Terminal - https://aliexpress.com/item/4000029855783.html
    * Connector - https://aliexpress.com/item/32715864245.html

* Display - <del>OLED 0.96`, Rotary Switch, Speaker</del>
    * Zonestar OLED Display - https://aliexpress.com/item/4000839370779.html

## Todo
* [ ] <del>Schematic, Pin map for display</del>
* [V] Mount model for display
* [ ] Marlin configuragtion for Zonestar LCD using
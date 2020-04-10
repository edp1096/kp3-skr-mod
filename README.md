# Work for using silent board on Kingroon KP3

## Folders
* Marlin_SKR_E3_v12_KP3 : Marlin for SKR Board
* Mount : SKR board mounter on KP3 - STL, FreeCAD files

## Marlin bugfix 2.0.x
* Marlin code from BIQU github and I fix a bug which not working save.
* Instead of stock tft-24, I created my own display unit using `oled 0.96`
* Some pins were changed for using `oled 0.96`
    * I forgot pin map for `oled 0.96`, please see `HAS_SPI_LCD` section in `Marlin_SKR_E3_v12_KP3/Marlin/src/pins/stm32/pins_BTT_SKR_MINI_E3_V1_2.h`
* Using OLED_PANEL_TINYBOY2 in configuration.h
* `BLtouch` enabled. If you don't use it, disable it in `Configuration.h` and restore Z-stop definition in `pins_BTT_SKR_MINI_E3_V1_2.h`

## Mount
* I used freecad for design board mount.
* Not tested yet. You may should check and edit dimension.

## Parts you prepared
* Micro sd extension adapter
* USB mini-b extension cable
* Display
   * OLED 0.96"
   * Rotary Switch
   * Speaker

## Todo
* [ ] Schematic, Pin map for display
* [ ] Mount model for display

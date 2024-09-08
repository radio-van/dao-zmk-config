# ZMK Firmware for Dao keyboard

Based on [yumagulovrn/dao-zmk-config](https://github.com/yumagulovrn/dao-zmk-config)

### How to flash the keyboard?

1. Obtain `firmware.zip`
2. Unzip `firmware.zip` - you should have `dao_left.uf2` and `dao_right.uf2` files
3. Turn off the power for selected halve (move slider to position `OFF`)
4. Connect selected halve to the PC via USB-C cable
5. Press `RESET` button **twice** to enter DFU mode - you should see new USB device in your file manager
6. Copy the corresponding firmware to the root directory of the new USB device
7. Disconnect selected halve from the PC
8. Repeat steps 3-7 for the other halve

### How to pair halves?

1. Turn off the power for both halves (move slider to position `OFF`)
2. Turn on the power for both halves (move slider to position `ON`)
3. Press `RESET` button **once** on both halves **simultaneously**


# Changelog

### v3
Goal is to minimaze usage of edge columns, on the way to 36 keys.
* (test) `quote` and `double_quote` produces double-and-cursor-between on **hold**
* `minus` and `plus` above `9` and `0` on **SYM** layer
* `(` and `)` on `N` and `M` on **SYM** layer
* `~` and `grave` on `Z` and `/` on **SYM** layer
* `insert` on left-bottom corner (temporary)
* combos:
    * `FG` = `space`
    * `YU` = `[]`
    * `HJ` = `{}`
    * `NM` = `()`
* tap-dances:
    * `F` = `ESC`
    * `E` = double `grave`
    * `R` = `~`
* fix space macro to proper exit from **SYM** layer

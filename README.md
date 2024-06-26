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


# Current layout
```
DEFAULT:
` ``         Q    W    E           R         T           |      Y    RSHIFT U       I    O    P      - _
~ ``````     A    S    LCTRL D     LSFT F .  LGUI G      |      H           J       K    L    : ;    ' ''
kb layout    Z    X    C           V         B           |      N           M       ,    .    /      \ | ]
                       LALT INS    LCTRL     LSFT SPACE  |  LOWER       UPPER    TMUX 

LOWER:
()           !    @    #           $         %           |      ^           &       *    (    )      - 
{}           1    2    3           4         5           |      6           7       8    9    0      =
[]                {    }           [         ]           |      <           >       ,    .           + 
                                                                DEF         DEF 
UPPER:
F1           F2   F3   F4          F5        F6          |      HOME        END    
F7           F8   F9   F10         F11       F12         |      LEFT        DOWN    UP   RIGHT
BT0          BT1  BT2  BT3         BT4       BTCLR       |      PGDOWN      PGUP
                                                                DEF         DEF
```


# Changelog

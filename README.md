34 Key Layout Using ZMK For Ferris Sweep Split Keyboard

![Ferris Sweep v2.2](images/Ferris_Sweep.jpg)

This is a 34-key layout I created and use on my Ferris Sweep keyboard. Currently the keyboard has 7 layers:
Master half is left part of keyboard, slave - right.

## Layouts

**0 - main**<br />
![main](images/layouts/0-main.png)

**1 - num**<br />
![num](images/layouts/1-num.png)

**2 - symbol**<br />
![symbol](images/layouts/2-symbol.png)

**3 - fn**<br />
![fn](images/layouts/3-fn.png)

**4 - nav**<br />
![nav](images/layouts/4-nav.png)

**5 - mouse**<br />
![mouse](images/layouts/5-mouse.png)

**6 - bluetooth**<br />
![bluetooth](images/layouts/6-bluetooth.png)

## Combos

**1 - main**<br />
![main](images/combos/1-main.png)

**2 - symbol**<br />
![symbol](images/combos/2-symbol.png)

**3 - layer**<br />
![layout](images/combos/3-layer.png)

**4 - bootloader**<br />
![layout](images/combos/4-bootloader.png)

## How to configure and update firmware

1. Grab my working repository (https://github.com/dimadzhmil/zmk-config-sweep);
2. Create an account on github.com and fork this repository.
3. Connect your repository to the online ZMK configurator (https://nickcoutsos.github.io/keymap-editor/);
4. Change and save in the online configurator;
5. After 2-3 minutes the firmware archive will appear in the ZMK configurator (firmware.zip) - download;
6. Put the microcontroller in the firmware mode (press the uppermost right key for the left half, and press the uppermost left key for the right half), a new partition should appear - mount;
7. Rewrite the appropriate firmware for the half;
8. After 10 seconds~ the microcontroller will flash itself and reboot.
9. Enjoy.

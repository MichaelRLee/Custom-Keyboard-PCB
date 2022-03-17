# tenleeless

![tenleeless](imgur.com)

<table>
<th colspan=2 style="text-align:center">Firmware</th>
<tr>
<td><a href="https://github.com/MichaelRLee/qmk_firmware/tree/tenkeyless/keyboards/finz/tenleeless">QMK</a></td>
<td><a href="">Vial</a></td>
</tr>
</table>

A hotswappable tenkeyless board, designed  with using a Teensy 3.2 as the controller.  Other controller boards with the same pinout (like the Teensy LC), should be usable, or any board with enough pins if not using pin headers (though adjustments to the QMK firmware would be needed).

### Design notes

The gap between the function keys and the alphanumeric cluster, as well as between the cluster and the nav keys, is 0.25u.  The spacebar stabalizer is the only one that has been flipped (wire north of the switch).  Any non-tray mounted mounting plate that fits the above should work with this PCB, though it was designed using a kbd8x plate as reference.

The board was is limted to a 7u space bar (1.5u ctrl/alt keys and 1u win keys, no fn/menu key), as well as a stepped caps lock.

As the microcontroller is located above the left arrow key, you may want to use a daughterboard (or female USB port).
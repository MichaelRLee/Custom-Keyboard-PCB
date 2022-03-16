# leepad

![leepad](imgur.com)

<table>
<th colspan=2 style="text-align:center">Firmware</th>
<tr>
<td><a href="https://github.com/MichaelRLee/qmk_firmware/tree/numpad/keyboards/finz/leepad">QMK</a></td>
<td><a href="https://github.com/MichaelRLee/vial-qmk/tree/numpad/keyboards/finz/leepad">Vial</a></td>
</tr>
</table>

A hotswappable numpad with extra macro keys.  Designed with the intention of using a Pro Micro as the controller, though the the spacing between the two PTH collumns do not reflect this.  What that means is that wires will have to be used in place of at least one row of pin headers.  The rational for this is to allow flexibility when mounting the Pro Micro (left or right side, or relocate the Pro Micro entirely).

Files (kicad and gerber) for a mounting plate are also included, which can easily be manufactured at the same time as the PCB.  For reference, the spacing between the macro keys and the rest of the keybaord is 0.25u, and all stabalizers have the wires facing inwards.
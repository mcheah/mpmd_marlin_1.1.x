_mpmd_marlin_1.1.x_

## MPMD_MARLIN_1.1.X

__an open-source upgrade for the Monoprice MP Mini Delta 3d printer__

The [mpmd_marlin_1.1.x](https:/github.com/aegean-odyssey/mpmd_marlin_1.1.x)
project combines Marlin firmware 1.1.9 along with a few customizations to
create a useful open-source firmware for the printer. Use the files in this
zip archive to enhance your Monoprice MP Mini Delta 3d printer.

### Card Contents

* mpmd_marlin_1.1.x firmware

  The several variants of the mpmd_marlin_1.1.x firmware are now available
online.

  Please see [latest release](https://github.com/aegean-odyssey/mpmd_marlin_1.1.x/releases/latest) to select and download your choice of firmware.
  
* G-code command files

  The setup_gcode folder contains a set of "command" (gcode) files
that extend the capabilities of the printer. Use the printer's
"print" function to perform calibrations, change or save settings,
and provide other capabilities that are normally not available on
the Monoprice Mini Delta printer.

* Example 3d models

  There are a few example .stl and .gcode files in the `/models` folder. The
.gcode files contain start and end gcode suited to the firmware and the MP
Mini Delta printer, and are ready to print directly from the micro SD card.

  * monoprice_cat
_(the Monoprice demo gcode file, with modified start gcode)_
  * 3dBenchy
_(ref: [#3DBenchy by CreativeTools.se](https://www.thingiverse.com/thing:763622))_
  * money_cat
_(ref: [maneki-neko -money cat- by bs3](https://www.thingiverse.com/thing:923108))_
  * money_cat_fill
_(ref: [maneki-neko -money cat- by bs3](https://www.thingiverse.com/thing:923108))_
  * treefrog_45_cut
_(ref: [Treefrog by MorenaP](https://www.thingiverse.com/thing:18479))_

* OctoPrint-plugin

  Use the plugin located in `/miscellany/OctoPrint` to allow for faster uploads
to the printer's micro SD card from within OctoPrint. Copy the single plugin
file, `ao_m990_upload_to_scard.py`, to OctoPrint's plugin folder.

  _Please see
[OctoPrint-plugin](https://github.com/aegean-odyssey/mpmd_marlin_1.1.x/wiki/OctoPrint-plugin)
for more information._


### Getting Started

_Please see
[the wiki](https://github.com/aegean-odyssey/mpmd_marlin_1.1.x/wiki)
for more information._

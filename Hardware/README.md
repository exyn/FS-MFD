## Hardware

KiCad project and exported Gerber files to use directly to order boards.

* Two-layer board, 142x142 mm, nothing special or unusual regarding vias, traces, pads, drilling or otherwise.
* Gerber/drill files have been used with JLCPCB to order PCB:s that are exactly as expected (their default options for a two-layer board, only thing requested was black solder-mask.
* The Gerber/drill files currently uploaded correspond to revision A of the board. There are a couple of minor changes that will be made in revision B that should make it into any files used to make PCB:s. It is nothing fatal but especially the toggle switch footprints need to be changed.
* The KiCad project also is at revision A. See above comment.
* There is a BOM generated with KiCad. The board works with many different manufacturers of cheap switches for instance though so it's worth checking out before getting anything more expensive. Same thing regarding the EC11 encoders. A big point here was to do a simple and cheap board to make it as available as possible.
* There might be a future revision prepared for a display, that has not really been decided yet though since this board is meant for VR first.
* The libraries imported to the project will be put in a libraries directory to make things a bit cleaner. Expect most of these minor things in a revision B update coming soon.

<br>

![image](https://github.com/exyn/FS-MFD/blob/main/Misc/FS-MFD%201.0alpha%20CAD.png)

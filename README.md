# Parallella Open Case and Cooling Kit

![A Parallella board fitted in a PARC-01 case](/images/Completed.jpg)

The [PARC-01 kit](http://abopen.com/PARC-01) is a simple but elegant case based on the "[sick of beige](http://dangerousprototypes.com/docs/Sick_of_Beige_basic_case_v1)" design, with low profile heatsinks and a DC fan to keep the [Parallella](http://www.parallella.org/) board cool. It can be bought from [Ground Electronics](http://groundelectronics.com).

## Repository contents

The case design is provided in the following formats:

* Adobe Illustrator (source)
* SVG
* PDF
* DXF

The top and bottom panels are laser cut from 3mm clear acrylic.

## Bill of materials

In addition to the acrylic parts the PARC-01 kit contains:

| Qty | Item                                |
| --- | ----------------------------------- |
|  1  | 25x25x8mm 5VDC fan                  |
|  1  | 15x15x8mm heatsink                  |
|  1  | 20x20x6mm heatsink                  |
|  8  | M3 16mm nylon screw                 |
|  4  | M3 12mm nylon screw                 |
|  4  | M3 nylon nut                        |
|  4  | M3 20mm nylon hex threaded spacer   |
|  4  | 3.2mm ID x 3mm circular nylon spacer|
|  4  | Clear 10mm diameter rubber foot/bumper|

## Fan power supply

J15 must be fitted in order to take power for the fan from the Parallella board mounting hole pads.

If the jumper is not already fitted, first locate J15.

![J15 open](/images/ParallellaJ15.jpg) 

1. Cut a ~6mm or so piece of solid core hook-up wire and bend this into a U shape, with the two ends around 3mm apart. 

2. Insert this into J15, but note that it may not drop all the way in as there is a Samtec connector directly under one of the pads.

3. Solder the link in place from the top side of the board.

![J15 fitted](/images/ParallellaJ15Fitted.jpg)

## Assembly

1. Remove the protective plastic from the acrylic panels.

2. Place the top panel face down (writing going the wrong way).

3. Place the fan on top, with the label facing upwards and the leads pointing towards the hole for the UART header.

4. Fix the fan in place with 4x M3 16mm nylon screws and 4x M3 nylon nuts.

5. Use wire cutters to trim the screws close to the nuts.

   ![Top panel with fan fitted](/images/TopFan.jpg)

6. Fix the rubber feet to the base panel, just inside — but not covering! — the four holes.

7. Push the remaining M3 16mm nylon screws up through the base panel, and drop the 3mm circular spacers on top.

   ![Base panel with screws and circular spacers](/images/BaseScrewsSpacers.jpg)

8. Place the Parallella board on top of the spacers.

   ![Base with Parallella](/images/BaseParallella.jpg)

9. Fit the heatsinks to the Epiphany and Zynq chips. Note that two 15x15mm heatsinks are pictured above, but with v1.1 kits that are supplied with one 15x15mm blue and one 25x25mm silver heatsink, the smaller should be fitted to the Epiphany and the larger to the Zynq.

10. Connect the fan +ve solder tag (red wire) to the mounting hole pad next to the barrel jack power connector.

11. Connect the fan -ve solder tag (blue wire) to the mounting hole pad next to the Ethernet connector.

16. Screw the four nylon hex spacers down onto the screws.

17. Place the top panel on the hex spacers and fix in place with 4x M3 12mm nylon screws. 

   ![Fan power supply points](/images/PowerPoints.jpg)

## Changelog

| Version | Date     | Summary                              |
|---------|----------|--------------------------------------|
| 1.0     | 25/06/14 | Initial version.                     |
| 1.1     | ?        | Larger Zynq heatsink, and fan with 4 mounting holes and pre-terminated leads |

_Note that v1.1 kits started shipping at some point mid-late Summer 2014._

## Licence

Parallella Open Case and Cooling Kit copyright 2014, 2015 [AB Open Ltd](http://abopen.com).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Thanks

With thanks to [Oomlout](http://oomlout.co.uk/) for their help with design and prototyping.

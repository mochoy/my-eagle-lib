# my-eagle-lib
Library of "custom" components, with packages, symbols, and descriptions I use in Eagle CAD. 

### Don't click on the files! 

[Click here](https://github.com/mochoy/my-eagle-lib/zipball/master) 
to download this as a zip file.

### Installation

1. Open Eagle and select the `Control Panel` window.
2. Choose `Options` and from the drop down that appears, `Directories`.
3. Change the Libraries line from: `$EAGLEDIR/lbr` to something like:

    > $EAGLEDIR/lbr:$HOME/external_lbrs (for OS X)

    > $EAGLEDIR\lbr;$HOME\external_lbrs (for Windows)

4. Click `OK` to save your changes.
5. Eagle will prompt to create the directory if it does not already exist. Note 
the location and choose `Yes` to create the directory.

    > On OS X, `$HOME/external_lbrs` changes to: /Users/mosfet/external_lbrs/
   
    > On Windows, `$HOME\external_lbrs` changes to: C:\Users\Mosfet\Documents\external_lbrs

6. Find and open the `external_lbrs` folder. Unzip and drag `adafruit.lbr` into the 
   new `external_lbrs` folder.
7. Restart Eagle. The library should be now be usable. 


### List of Components

I'll hopefully keep this updated


- [PSMN1R5-30YLC MOSFET](https://assets.nexperia.com/documents/data-sheet/PSMN1R5-30YLC.pdf) - LFPAK/SO8 N-channel 30 V 100A 1.55mΩ logic level MOSFET

- 1.8mm Padded mounting hole

- 2.8mm Padded mounting hole

- [MIC4606](http://ww1.microchip.com/downloads/en/DeviceDoc/20005852A.pdf) - Half-bridge MOSFET driver, TTL input, wide operating voltages

- [SRA-12VDC-CL Relay](https://datasheet.lcsc.com/szlcsc/Ningbo-Songle-Relay-SRA-12VDC-CL_C60169.pdf) (Sat, 01/05/19) - 3V, 5V, 6V, 9V, 12V, 18V, 24V 20A relay 

- 1.3mm Padded mounting hole (Sat, 01/05/19) - Used for relay legs

- [SRA-12VDC-CL Relay](https://datasheet.lcsc.com/szlcsc/Ningbo-Songle-Relay-SRA-12VDC-CL_C60169.pdf) with oval pads (Sun, 01/10/19) - 3V, 5V, 6V, 9V, 12V, 18V, 24V 20A relay 

- XT60-PW male connector

- XT60-PW female connector

- [BTN8982TA](https://static6.arrow.com/aropdfconversion/e0e03f0407d2fe3b1d7e79e076707c2d910a3b0e/btn8982ta-data-sheet-rev10-infineon.pdf) (Sun, 04/28/19) - Half bridge motor driver

- Arduino Nano (Sun, 05/12/19)

- Motor Tab Hole (Sat, 05/18/19, updated Sun, 06/30/19) - Hole in rectangle pad to solder motor tabs

- 3mm Padded Mount Hole (Sun, 06/09/19) - Mounting holes for Nerf screws

- [74LVC1G07](https://www.diodes.com/assets/Datasheets/74LVC1G07.pdf) (Thur, 07/04/19) - Single open drain buffer output

- 3mm Unplated Mount Hole (Sun, 07/21/19) - Unplated mount hole for Nerf Screws. Good if used near components that will be hand soldered so solder can't get on hole's copper plating

- [INA181](http://www.ti.com/lit/ds/symlink/ina181.pdf) (Sat, 08/31/19) - Bidirectional, low- and high-side voltage output, current-sense amplifiers

- [CH340G](http://www.handsontec.com/dataspecs/ch340g.pdf) (Fri, 11/15/19) - USB to UART interface IC. The datasheets for this part are relatively sparse, so [here's](https://cdn.sparkfun.com/datasheets/Dev/Arduino/Other/CH340DS1.PDF) another datasheet for a parts in the same CH340 family.


### Sources

- Create packages and symbols using [this](https://electronics.stackexchange.com/questions/16030/new-eagle-library-reuse-standard-package-symbol)

- More help with symbols [here](https://www.autodesk.com/products/eagle/blog/library-basics-part-2-creating-first-symbol-autodesk-eagle/)

- SOT669 package and symbol stolen from [here](https://www.mikrocontroller.net/topic/236049)

- Using [Adafruit's Eagle Lib](https://github.com/adafruit/Adafruit-Eagle-Library)'s parts

- SOIC-8 package from [here](https://github.com/open-ephys/eagle-libraries)

- Pin symbols from Rembrandt Electronics's JST connector library [here](https://www.rembrandtelectronics.com/product/eagle-libraries/) and [here](https://www.diymodules.org/eagle-show-library?type=usr&id=1012211612&part=Rembrandt+Electronics+-+JST+XH+Connectors+v1-0.lbr)

- SOT23-6 & SOIC-8 package from [here](https://github.com/sparkfun/SparkFun-Eagle-Libraries)

- SOT223-3 package from [here](https://github.com/shimniok/eagle-library)


### List of Packages Different from List of Components


- LFPAK/SO8 Extended: larger base pad and leg pads for easier soldering


# my-eagle-lib
Library of "custom" components, with packages, symbols, and descriptions I use in Eagle CAD. 

### Don't click on the files! 

[Click here](https://github.com/etnom/my-eagle-lib/zipball/master) 
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


### Sources

- Create packages and symbols using [this](https://electronics.stackexchange.com/questions/16030/new-eagle-library-reuse-standard-package-symbol)

- More help with symbols: https://www.autodesk.com/products/eagle/blog/library-basics-part-2-creating-first-symbol-autodesk-eagle/

- SOT669 package and symbol stolen from [here](https://www.mikrocontroller.net/topic/236049)

- Using [Adafruit's Eagle Lib](https://github.com/adafruit/Adafruit-Eagle-Library)'s parts

- SOIC-8 package from [here](https://github.com/open-ephys/eagle-libraries)

- Pin symbols from Rembrandt Electronics's JST connector library [here](https://www.rembrandtelectronics.com/product/eagle-libraries/) and [here](https://www.diymodules.org/eagle-show-library?type=usr&id=1012211612&part=Rembrandt+Electronics+-+JST+XH+Connectors+v1-0.lbr)


### List of Components


I'll keep this updated hopefully


- [PSMN1R5-30YLC MOSFET](https://assets.nexperia.com/documents/data-sheet/PSMN1R5-30YLC.pdf) - LFPAK/SO8 N-channel 30 V 100A 1.55mΩ logic level MOSFET

- 1.8mm Padded mounting hole

- 2.8mm Padded mounting hole

- [MIC4606](http://ww1.microchip.com/downloads/en/DeviceDoc/20005852A.pdf) - Half-bridge MOSFET driver, TTL input, wide operating voltages

- [SRA-12VDC-CL Relay](https://datasheet.lcsc.com/szlcsc/Ningbo-Songle-Relay-SRA-12VDC-CL_C60169.pdf) (Sat, 01/05/19) - 3V, 5V, 6V, 9V, 12V, 18V, 24V 20A relay 

- 1.3mm Padded mounting hole (Sat, 01/05/19) - Used for relay legs

### List of Packages Different from List of Components


- LFPAK/SO8 Extended: larger base pad and leg pads for easier soldering


# my-eagle-lib
Library of components, with packages, symbols, and descriptions, I use in Eagle CAD. 

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

- SOT669 package and symbol stolen from [here](https://www.mikrocontroller.net/topic/236049)

- Using [Adafruit's Eagle Lib](https://github.com/adafruit/Adafruit-Eagle-Library)'s parts


### List of Components


I'll keep this updated hopefully


- [PSMN1R5-30YLC MOSFET](https://assets.nexperia.com/documents/data-sheet/PSMN1R5-30YLC.pdf) - SOT699 N-channel 30 V 100A 1.55mΩ logic level MOSFET


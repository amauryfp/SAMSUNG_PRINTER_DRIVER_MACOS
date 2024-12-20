# Samsung Printers Drivers for MacOs

This repository contains Samsung printer drivers extracted from legacy MacOS driver support, ensuring compatibility with newer MacOS versions, including those running on M Series ARM-based processors. These drivers enable seamless functionality for Samsung printers on modern MacOS systems, preserving usability despite the discontinuation of official support.

## Driver Installation

Open terminal and do the repository clone:

    git clone https://github.com/amauryfp/SAMSUNG_PRINTER_DRIVER_MACOS.git

Navigate to repository folder:

    cd SAMSUNG_PRINTER_DRIVER_MACOS/

Simply copy the content of the following repository folders using terminal as described below:

    sudo cp -rfv Samsung /Library/Printers/ && sudo cp -rfv PPDs /Library/Printers/
    
## Printer installation

With the drivers copied in the desired folder, simply follow the steps for adding your printer normally.

## Final cleanup

After installation you can simply delete this repository folder.

    cd .. && sudo rm SAMSUNG_PRINTER_DRIVER_MACOS/
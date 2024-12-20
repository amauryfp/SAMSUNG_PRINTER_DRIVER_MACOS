# MacOs Driver for Samsung Printers

This repository contains Samsung printer drivers extracted from legacy MacOS driver support, ensuring compatibility with newer MacOS versions, including those running on M Series ARM-based processors. These drivers enable seamless functionality for Samsung printers on modern MacOS systems, preserving usability despite the discontinuation of official support.

## Driver Installation

Repository clone:

    git clone https://github.com/amauryfp/samsung_printer_driver_macos.git

Simply copy the content of the following repository folders using terminal as described below

> Assuming you are with your terminal open and in the root folder of repository

    sudo cp -rfv Samsung /Library/Printers/ && sudo cp -rfv PPDs /Library/Printers/
    
## Printer installation

With the drivers copied in the desired folder, simply follow the steps for adding your printer normally.

## Final tweak

After installation you can simply delete this repository folder.
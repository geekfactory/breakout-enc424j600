# Breakout board for ENC424J600

This board implements a network interface based on the ENC424J600 Ethernet controller from Microchip Technology. All the required components to stablish an Ethernet link are contained in this board.

The signals required to communicate with a host processor are broken out to standard pitch headers. Status leds are provided to show the link and transmission status.

![Breakout board for ENC424J600](https://raw.githubusercontent.com/geekfactory/breakout-enc424j600/master/extras/breakout-enc424j600.JPG)


## Features and hardware details

* On-board RJ-45 Jack with magnetics and ethernet controller (MAC and PHY layers)
* Small circuit footprint which fits solderless breadboards
* Requires 3.3 V power supply. No on-board regulation or level shifting provided
* Globally unique MAC address for easy deployment
* Standard header connections for easy prototyping on breadboards and protoboards

## Repository contents

1. __root__ - EAGLE Source files for the board
2. __/documents__ - Additional documentation, datasheets and assembly instructions
3. __/production__ - History of gerber files sent for production
4. __/extras__ - Technical drawings, mounting hardware and related accessories
4. __/firmware__ - Testing or definitive firmware for this board

## Hardware revisions

* 1.0 - First revision

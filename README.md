## The m5pl-scuffed mechanical keyboard build guide

The m5pl-scuffed is a handwired mechanical keyboard made for enthusiasts on the cheap.<br>
The total cost of the keyboard should be around 150 USD.<br>
Let's get started!

## Parts

To build this keyboard, you'll need:

- A 60% keyboard case and plate
- Wires (these can be stolen from a USB cable and such)
- Enough diodes for all of the keys on the board
- A SAMD based Arduino or compatbile MCU, I'm using an Arduino Nano 33 IoT
- Mechanical key switches, these are based on preference but I personally picked Akko CS Red Rose Switches.
- Key caps, these can use any profile since we'll have plenty of free space in the case due to not having a full size PCB.

## The build

We'll start by grabbing our key switches and assembling them in the plate. They should simply snap in place.<br>
Now we're ready to start wiring: we'll heat our soldering iron to around 300°C (570°F) and grab our wires. I suggest exposing bits of your wire at intervals, by cutting the shrink wrap intermittently.<br>
Let's put some fresh solder on the higher pins of our switches and start soldering them in columns on every exposed spot of the wire.

(image here tbd)

When we're done with soldering each pin in columns, we can grab our diodes.<br>
Put solder on the lower pin of every switch and solder one end of the diode to it.
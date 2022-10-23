# PAR124-Nixie-Display
Bought a PAR124 Lock-in Amplifier from Ebay and the item arrived smashed into bits. I restored the unit and made a cool nixie display for it.


The machine uses time divison demultiplexing to drive 5 nixie tubes in sequence, to reduce the needed I/O (15 versus. 50). The board uses priority encoders and decade
counters to even further simplfy the process of writing into the display. An M5Stack ADS1115 bi-polar I2C voltmeter is used to read the output voltage of the amplifier.
The winding that is used to power the front illuminantion bulbs of the PAR were tapped off and a CUI devices VX78039-1000 to produce a Nano Every. 

Enjoy!

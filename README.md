# MoteinoUSB-LP
Moteino USB (R5) with a voltage level shifter (TI [SN74LVC1T45](http://www.ti.com/lit/ds/symlink/sn74lvc1t45.pdf)) to isolate current sources. This prevents parasitic current draw through FTDI's RX pin when USB is unplugged and lowers overall sleep current draw to almost the same as a base Moteino without FTDI. Measured current draw with voltage level shifter: ~6.6uA.

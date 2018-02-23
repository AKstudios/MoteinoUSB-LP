# MoteinoUSB-LP
Moteino USB (R5) with a unidirectional voltage level shifter (TI [SN74LVC1T45](http://www.ti.com/lit/ds/symlink/sn74lvc1t45.pdf)) to isolate current sources. This prevents parasitic current draw through FTDI's RX pin when USB is unplugged and lowers overall sleep current draw to almost the same as a base Moteino without FTDI. Measured current draw with voltage level shifter: ~6.6uA.

Alternative design using an N-channel MOSFET for voltage level shifting also included. This is cheaper than using the level shifter and lowers the current draw to ~6.4uA.

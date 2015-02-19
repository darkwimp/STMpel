# STMpel

An open source Scanning Probe Microscope


0.) General Information

Design based on Dan Berard´s STM [1]

Frame based on Hexagon V_I from fablab-kalsruhe.de [2]

1.) Frame


2.) Electronics

No final decision has yet been made on which architecture the software is going to run on. 

2.1) DAC
Dan´s doc does not include documentation or code for the 4-channel digital-analog converter DAC8734 [3]
As of 19.02.2015 there seems to be a problem in SPI comms, losing the MSB of each Byte. 

Still, a simple Arduino sketch managed to fiddle with the output levels of the DAC. 

X.) Links

[1] http://dberard.com/2015/01/12/a-home-built-scanning-tunneling-microscope-with-atomic-resolution/

[2] http://wiki.fablab-karlsruhe.de/doku.php?id=projekte:hexagon

[3] http://www.ti.com/product/dac8734
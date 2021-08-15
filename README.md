# GLCD-KS0108-with-Arduino-Due-
Graphic Display KS0108 with Arduino Due (ARM)

Drive GLCD with ks108 driver by means of Arduino Due.
The Code was test and evaluated on Arduino Due Board. 

Connections for ks0108 GLCD panels (8bit comunication):

    GLCD    Due
   
    D0----> 52    
    D1----> 50
    D2----> 48
    D3----> 46
    D4----> 53
    D5----> 51
    D6----> 49
    D7----> 47
    EN----> 32
    CS1----> 36
    CS2----> 37
    DI----> 31
    RW ----> 30
    
 * The other pins of GLCD are routinely connected.



Before using this code, please download and install U8glib library:
https://github.com/olikraus/u8glib/wiki


Manual for U8glib:
https://github.com/olikraus/u8glib/wiki/userreference


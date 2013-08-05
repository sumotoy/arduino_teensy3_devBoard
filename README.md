arduino teensy3 devBoard V1
===========================

A development board for Arduino/Teensy3 with level convertes onboard.

I've build this board for easily test various issues I have with beradboard because when speed it's high and wires are caotic or not stables (plus on breadboard it's almost impossible apply a correct decoupling) it became a nightmare figure out what's really going on. The board has a high power 3v3 regulator, an LCD that use a gpio so it just use 3 wires (with my library posted here in github), several bidirectional level changer that are bypassable, a port for a rf tranceiver, a protection chip that test current and voltage and some connectors. I've builded several addition card to study a combination of interfaces and with the main card it's easy to crossdevelop from arduino uno and teensy3

![devboard](http://i1189.photobucket.com/albums/z437/theamra/CIMG1499.jpg)

Here's the expansion board 1 for study interface and displays

![devboard](http://i1189.photobucket.com/albums/z437/theamra/CIMG1500.jpg)




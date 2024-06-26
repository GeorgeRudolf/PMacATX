# PMacATX
ATX Adapter for some PowerMacs

Made for my own 8100 because I just have a bare board with no real PSU, this should also fit other things with a 22-way connector, including some PCI PowerMacs. For those you'll need the 3.3V auxiliary harness - a spot to solder it in has been provided on the PCB.

![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/ff40ac33-56cd-4715-9351-53752c71fa98)

This comes with no warranty. I'm not responsible if your machine explodes.

Instructions:

1- Download the files from this repo

2- Stuff them into JLCPCB's website, selecting assembly

3- Ignore warnings about missing parts (the BoM includes the connectors which aren't used there) and order boards

4- Buy the connectors while you wait for the boards to arrive

5- Using a box cutter or similarly sharp thin blade, trim the 24-way connector like so:
![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/94a20cf3-9d9f-49c7-bded-f7e1aba15d30)

For the love of what's holiest, pay attention to which end of the connector you're chopping two pins off on. It's the end opposite to the one with the little nub above the locating peg.

6- Solder connectors to board

7- Plug into Mac

9- Have fun

Alternately, use the gerbers with your favorite PCB house and just buy the two SMD parts listed in the BoM separately.

Schematics for the curious:
![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/a955cce4-3d1f-4474-9e2d-e95dd54c1e48)


An alternate version is provided for chinese MiniFit connectors with odd spacing. A reshaped version has been added to hopefully avoid the need for filing - thanks to croissantking at 68kmla for testing on a Q840av

Original, filed to fit without modifying case
![IMG_8652](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/87544aad-1d49-4329-82e7-cdf7fe7cf250)
![IMG_8651](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/86463f56-0742-4779-a5d5-d2ee0a68889e)

Reshaped version
![1718070307856](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/3a5068b8-6118-4eef-a114-017a085f5599)



# PMacATX
ATX Adapter for some PowerMacs


Made for my own 8100 because I just have a bare board with no real PSU, this should also fit other things with a 22-way connector, including some PCI PowerMacs. For those you'll need the 3.3V auxiliary harness - a spot to solder it in has been provided on the PCB.

![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/da456385-260d-4bc0-ab6d-d4907ef4cab8)


This comes with no warranty. I'm not responsible if your machine explodes.

Instructions:

1- Download the files from this repo

2- Stuff them into JLCPCB's website, selecting assembly

3- Ignore warnings about missing parts (the BoM includes the connectors which aren't used there) and order boards

4- Buy the connectors while you wait for the boards to arrive

5- Using a box cutter or similarly sharp thin blade, trim the 24-way connector like so:
![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/361f2e9c-0fa3-4f40-a7f2-113a861e6988)
For the love of what's holiest, pay attention to which end of the connector you're chopping two pins off on. It's the end opposite to the one with the little nub above the locating peg.

6- Solder connectors to board

7- Plug into Mac

9- Have fun

Alternately, use the gerbers with your favorite PCB house and just buy the two SMD parts listed in the BoM separately.

Schematics for the curious:
![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/4b16d9e6-9e32-4598-8167-f9040eeb1a20)

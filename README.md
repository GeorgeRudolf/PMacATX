# PMacATX
ATX Adapter for some PowerMacs


Made for my own 8100 because I just have a bare board with no real PSU, this should also fit other things with a 22-way connector, including some PCI PowerMacs. For those you'll need the 3.3V auxiliary harness - a spot to solder it in has been provided on the PCB.

![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/19d45def-aec6-44e8-b74d-0e8084304dd6)



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
![image](https://github.com/GeorgeRudolf/PMacATX/assets/24400566/8e475dac-4ac2-4d16-af47-5ea85f9ff2cb)



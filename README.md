# Buffs-and-Tap-for-DIY-in-Voron
Inexpensive reinforcements with a tap for self-made for voron 2.4

Hello

Over three years ago I built my first voron, then still 2.2. I have it in a rather large size 450*3. As after these few years it is quite different from the current news, it's time to update the printer. New electronics M8P+CB1 and EBB Can 2209 arrived, also voron-tap.

After these updates and the resulting increase in the weight of the entire head, it turned out to be necessary to reduce the "max_accel" parameter and extend the entire printing process.
The main reason after the initial measurements turned out to be the plastic connections of the Tap (3D printing) and the connections of the bogies on the "Y" axis
There are several ready-made solutions on the CNC market for these stiffeners, but I like to do something myself. And this is how I designed the "X" and "Y" reinforcements and Tap.
I know that many people have their own plotters or mini cnc milling machines, or access to them. There are also a large number of people who like manual and can do something with their own hands, this is my post for you. For both modes, it is necessary to purchase a 2mm aluminum sheet, preferably PA9 or another with similar properties. And an aluminum pipe fi 10/1mm.
## XY reinforcements<br/>

![Image of XY reinforcements by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230516_125437371_iOS-m.jpg)

The only printed element is the stop end stop for X. The rest can be cut on cnc or by hand and thread M5 holes in the lower elements.
We need to cut the tube (precisely) <br/>
* 4x30mm <br/>
* 2x20mm <br/>
* 8x10mm <br/>

Screws for threaded elements <br/>
* M5x35 - 10 pcs <br/>
* M5x45-2pcs <br/>
* 10 washers M5x1mm <br/>

We twist and we have a rigid connection, it worked perfectly for me.
![Image of XY reinforcements by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230517_072044929_iOS-m.jpg)
![Image of XY reinforcements by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230517_072039420_iOS-m.jpg)

  Most questions will be answered by looking at the design in the CAD catalog file for DesignSpark Mechanical.<br/>

![Image of XY reinforcements by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/dsm1-m.jpg)
![Image of XY reinforcements by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/dsm2-m.jpg)

## TAP<br/>
As before, we cut out elements from 2mm sheet metal and thread selected M3 holes. We print elements from the STL catalog. In some cases, it will probably be necessary to change the attachment element of the optical endstop for "Z", depending on its type. (I have my own design) You will need to change it in DesignSpark Mechanical. I pasted the magnet for the tap 7/3mm. <br/>

![Image of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230516_163716491_iOS-m.jpg)
![Image of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230516_171852115_iOS-m.jpg)
![Image of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230516_173454670_iOS-m.jpg)
![Image of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/20230516_203652587_iOS-m.jpg)
![Image of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/dsm3-m.jpg)
![Video of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/tap-test.gif)

This project works perfectly for me. There is a noticeable change in the stiffness of the entire carriage with the extender.

![Video of Tap by Mario](https://github.com/mario73z/buffs-and-Tap-for-DIY-in-voron/blob/main/Jpg/tap-run.gif)

Some CAD design elements were downloaded from https://github.com/VoronDesign/

Although it is a simple project and works great for me, and its assembly was not difficult, I still strongly encourage you to familiarize yourself with the project and your own skills for such work before you decide to make changes. Reinforcements and Tap in the CNC version can be purchased ready-made on the market for several dozen euros. I am not responsible for any failures and possible defects. However, satisfaction from the work done brings a lot of satisfaction and, of course, this does not exclude possible substantive assistance on my part. Be careful and good luck. ;)
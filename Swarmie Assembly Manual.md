# Building a Swarmie

## Table of Contents
1.  [Introduction](#1---introduction)
2.  [Guide to 3D Printed and Laser-Cut Parts](#2---guide-to-3d-printed-and-laser-cut-parts)
  - [3D Printed Parts](#3d-printed-parts)
  - [Laser-Cut Parts](#laser-cut-parts)
3.  [Preparation – Drilling, Tapping, and Soldering](#3---preparation--drilling-tapping-and-soldering)
  - [GPS/IMU Mount](#gpsimu-mount)
  - [NUC Base](#nuc-base)
  - [Battery Base and Battery Brace](#battery-base-and-battery-brace)
  - [Ultrasound Tower](#ultrasound-tower)
  - [Solder IMU Headers](#solder-imu-headers)
4.	[Chassis Assembly](#4-chassis-assembly)
  - [Brackets](#brackets)
  - [Motors](#motors)
  - [Tire Assembly](#tire-assembly)
  - [Bottom Plate and Battery](#bottom-plate-and-battery)
  - [Wheel Attachment](#wheel-attachment)
5.	[Top Plate Assembly](#5-top-plate-assembly)
  - [3D Printed Parts](#3d-printed-parts)
  - [Ultrasound Sensor Mounting](#ultrasound-sensor-mounting)
  - [NUC Base, Camera, IMU, GPS](#nuc-base-camera-imu-gps)
  - [PCB, Switch, and Bus Connections](#pcb-switch-and-bus-connections)
  - [NUC Assembly](#nuc-assembly)
  - [Cover Plate Assembly and Attachment](#cover-plate-assembly-and-attachment)
  - [Top Plate Attachment](#top-plate-attachment)
6.	[Fully Assembled](#6-fully-assembled)

## 1.	Introduction
This manual is the complete guide to constructing a Swarmie.  Construction is intended to be done in the order presented, but many portions are independent of each other.

Notes:
- All metric screws are colored black.
- All imperial screws are stainless steel, with the exception of two 2-56 nylon screw sizes.
- All holes in the 3D printed parts originally come filled with wax. Drilling these out should be effortless.  If it is not, you may have drilled too much or in an incorrect location.

**Warning:** Do not over-tighten screws in the 3D printed parts.  Tapping these parts is effective, but the threads are likely to be stripped if screws are over-tightened.

## 2.	Guide to 3D Printed and Laser-Cut Parts
### 3D Printed Parts

![Battery Base](http://swarmathon.cs.unm.edu/img/BatteryBase.png)
Figure 1: Battery Base

![Battery Brace](http://swarmathon.cs.unm.edu/img/BatteryBrace.png)
Figure 2: Battery Brace

![Battery Cross Strap](http://swarmathon.cs.unm.edu/img/BatteryCrossStrap.png)
Figure 3: Battery Cross Strap

![Camera Mount](http://swarmathon.cs.unm.edu/img/CameraMountLW.png)
Figure 4: Camera Mount

![GPS/IMU Mount](http://swarmathon.cs.unm.edu/img/GPS_IMUMountLW.png)
Figure 5: GPS/IMU Mount

![Lid Support](http://swarmathon.cs.unm.edu/img/LidSupportLW.png)
Figure 6: Lid Support

![NUC Base](http://swarmathon.cs.unm.edu/img/NUCBasePCB.png)
Figure 7: NUC Base

![Ultrasound Tower](http://swarmathon.cs.unm.edu/img/USTowerLW.png)
Figure 8: Ultrasound (US) Tower

###	Laser-Cut Parts

Each of the laser-cut parts comes covered in a brown protective film.  You can remove the film using a fingernail.
 
![Bottom Plate](http://swarmathon.cs.unm.edu/img/BottomPlate.png)
Figure 9: Bottom Plate

![Top Plate](http://swarmathon.cs.unm.edu/img/TopPlate.png)
Figure 10: Top Plate

![Cover Plate](http://swarmathon.cs.unm.edu/img/CoverPlate.png)
Figure 11: Cover Plate

## 3.	Preparation – Drilling, Tapping, and Soldering

A few of the 3D printed parts have holes that need to be drilled and tapped.  These holes sometimes are filled with wax, but you can drill it out easily.  Tap lubricant should not be needed as the holes were all filled with wax at one point.

###	GPS/IMU Mount

Use a #50 drill bit to drill out the hole shown in the picture below.

![GPS/IMU Mount w/ Holes](http://swarmathon.cs.unm.edu/img/Holes%20Highlighted/GPS_IMUMountLW.png)
 
Use a 2-56 tap to tap the hole.

Note: this hole will be used for securing the IMU using a 2-56x1/2” nylon screw.

###	NUC Base

Use a #50 drill bit to drill out the holes indicated in the picture below.  These holes should not be drilled all the way through.  The holes come filled with wax, so drilling into them should feel soft.  Once you feel some resistance, you have drilled through all of the wax, stop drilling.

![NUC Base w/ Holes](http://swarmathon.cs.unm.edu/img/Holes%20Highlighted/NUCBasePCB.png)

Use a 2-56 tap to tap the holes.

###	Battery Base and Battery Brace

Use a #43 drill bit to drill out the four holes indicated in the picture below.  The holes can be drilled through to the gap below them.
 
![Battery Base w/ Holes](http://swarmathon.cs.unm.edu/img/Holes%20Highlighted/BatteryBase.png)

![Battery Brace w/ Holes](http://swarmathon.cs.unm.edu/img/Holes%20Highlighted/BatteryBrace.png)

Use a 4-40 tap to tap the holes.

###	Ultrasound Tower

Use a #43 drill bit to drill out the 10 holes indicated in the picture below.  Warning: holes 1 and 2 are not through holes. You should be able see through the material to know how deep to drill.

![Ultrasound Tower w/ Holes](http://swarmathon.cs.unm.edu/img/Holes%20Highlighted/USTowerLW.png)

 Use a 4-40 tap to tap the holes.  Note: because holes 1 and 2 are not through holes, you may need to partially tap them, remove and clean the tap, then finish tapping.  

### Solder IMU Headers

The IMUs come with two sets of headers, use only the straight set.  First, trim off one of the headers, only five are needed.  Solder the header onto the IMU as shown in the picture below.

![Soldered IMU](http://swarmathon.cs.unm.edu/img/SolderedIMU.jpg)
 
## 4. Chassis Assembly

###	Brackets

Tools:
-	Phillips head screw driver

Parts:
-	Chassis kit: The kit comes with two pairs of brackets and two laser-cut plates.  These laser-cut plates are not used, they can be thrown away.  The Swarmie is made with three laser-cut plates packaged separately.

Using eight M3x6mm screws, attach all four brackets together as seen in the following images.  Note that the two side brackets are not symmetrical and should be attached in the same orientation.  

![Chassis Side Brackets](http://swarmathon.cs.unm.edu/img/ChassisSideBrackets.jpg)

![Chassis Top](http://swarmathon.cs.unm.edu/img/ChassisTop.jpg)

![Chassis Bottom](http://swarmathon.cs.unm.edu/img/ChassisBottom.jpg)

###	Motors

Attach motors to mounting holes using two M3x4mm screws per motor.  The motor shaft should be towards the bottom of the chassis.  See below for detail.

![Chassis w/ Motors](http://swarmathon.cs.unm.edu/img/ChassisMotors.jpeg)

![Chassis w/ Motors, Labeled](http://swarmathon.cs.unm.edu/img/ChassisMotorsLabeled.jpg)

###	Tire Assembly

Wheel assembly instructions have been adapted from Lynxmotion’s instructions found [here](http://www.lynxmotion.com/images/html/build007.htm).

**Important:** half of the wheels must be assembled opposite to the other half.  This is to make sure that when they are attached to the Swarmie, they are all facing the same direction.  Example below:

![Wheels Opposite](http://swarmathon.cs.unm.edu/img/WheelsOpposite.jpg)
 
Notice that the tread is pointed in the same direction, but the inner wheels are in opposite orientations.

1.	First use a utility knife, or similar, to carefully remove any imperfections on the inner part of the rim. This will make things much easier later on.

  ![Tire 1](http://swarmathon.cs.unm.edu/img/tire01.jpg)

  Figure 12

2.	Pull one side of the tire out, so that it protrudes, like in the image. Insert one side of the rim. It helps to insert at an angle in the middle, where the opening is the largest. Rotate the rim slowly, while pressing it in, to help coax it into place.

  ![Tire 2](http://swarmathon.cs.unm.edu/img/tire02.jpg)
  
  Figure 13

3.	You should end up with the tire and rim looking like Figure 14.

  ![Tire 3](http://swarmathon.cs.unm.edu/img/tire03.jpg)
  
  Figure 14

4.	Pull out the side of the tire again, so that it looks like Figure 15.

  ![Tire 4](http://swarmathon.cs.unm.edu/img/tire04.jpg)
  
  Figure 15

5.	Gently press and rotate the rim into the tire. You want to end up with the rim almost fully into the tire with the bead still sticking out, as in Figure 16. If there are any imperfections leftover from Step 1, then it may be difficult to pass the tire over them.

  ![Tire 5](http://swarmathon.cs.unm.edu/img/tire05.jpg)
  
  Figure 16

6.	Quickly press the rim into the tire from both sides. The bead should now be completely in the flange. This step may require several attempts.

  ![Tire 6](http://swarmathon.cs.unm.edu/img/tire06.jpg)
  
  Figure 17

7.	Flip the tire over. It should look something like Figure 18. 

  ![Tire 7](http://swarmathon.cs.unm.edu/img/tire07.jpg)
  
  Figure 18

8.	Almost half the bead is in the flange. Just hold that side in and pull the rest of the bead away from the center, and it will retract back into the flange. It may be helpful to use a screw driver to pull the tire over the wheel.

  ![Tire 8](http://swarmathon.cs.unm.edu/img/tire08.jpg)

  Figure 19

9.	A completed tire is shown in Figure 20.

  ![Tire 9](http://swarmathon.cs.unm.edu/img/tire09.jpg)

  Figure 20

###	Bottom Plate and Battery

Tools:
-	1/16” hex key
-	3/32” hex key
-	¼” nut driver

Parts:
-	8x 4-40x1.5” screws – 3/32” hex key
-	4x 4-40x1/2” screws – 1/16” hex key
-	4x M3x6mm – 2.0mm hex key
-	16x washers
-	8x 4-40 nyloc nuts – ¼” nut driver
-	Battery Base
-	Battery Brace
-	Battery Cross Strap
-	Battery
-	Fire retardant bag

Using eight 4-40x1.5” screws and nyloc nuts, attach the battery base and battery brace.  The top of the battery brace has rounded edges. Use washers on both sides of the screws.  Make sure the screw heads are on the bottom.  The nylon inserts in the nyloc nuts should always face away from the screw heads.

![Bottom Plate w/ Battery Frame](http://swarmathon.cs.unm.edu/img/BottomPlateWithBatteryFrame.jpg)

The bottom of the chassis is the side in which the motor shafts are closest. Using four M3x6mm screws, attach the bottom plate to the bottom of the chassis. The plate can be attached in either orientation that it fits.  The orientation will matter later, when the wheels are attached.

![Bottom Plate Attached](http://swarmathon.cs.unm.edu/img/BottomPlateAttached.jpg)

Insert the battery into the fire retardant bag in the following way.  With the bag’s warning facing you, insert the battery with the wire leads coming out on the right, and the battery’s warning facing you.  

![Battery Out of Bag](http://swarmathon.cs.unm.edu/img/BatteryOutOfBag.jpg)

Close the Velcro flap and wrap it around the back of the bag as tightly as possible.  This is necessary to properly fit into the battery base.  

![Battery In Bag](http://swarmathon.cs.unm.edu/img/BatteryInBag.jpg)

Carefully lay the battery into the chassis to keep the bag tight. To maintain the tightness of the bag, insert it into the battery brace flap-side first, while holding onto the flap from underneath.

![Battery Slide in](http://swarmathon.cs.unm.edu/img/BatterySlideIn.jpg)

Then lower the other side to the battery base and press it in. The flap of the battery should be against the black acrylic of the bottom plate.

![Battery in Place](http://swarmathon.cs.unm.edu/img/BatteryInPlace.jpg)

Next, use four 4-40x1/2” screws (button head) to screw the battery cross strap to the battery base and battery brace.  This strap fits only one way, line up the holes and be sure that the flat side is against the battery.

![Battery Secured](http://swarmathon.cs.unm.edu/img/BatterySecured.jpeg)

###	Wheel Attachment

Tools:
-	3/32” hex key
-	3.5mm hex key

Parts:
-	2x mounting hub kit
-	4x assembled tires

Each mounting hub kit will contain two mounting hubs, two larger wheel screws, and three set screws. One set screw is extra.

Begin by screwing the wheel screws into the mounting hubs. Then slide the mounting hubs onto the motor shafts and screw on the set screw. The set screw should be screwed into the flat side of the motor shaft. The wheel screws are screwed on first to ensure the mounting hub is attached at the correct distance from the motor.  

![Mounting Hub](http://swarmathon.cs.unm.edu/img/MountingHub.jpg)

Unscrew the wheel screws, fit the wheel onto the mounting hub, and screw the wheel screw back in.  In the picture below you can see the direction in which the tires should be pointed.  The rear of the robot is considered to be the side of the larger battery base.

![Labeled Front/Rear of Chassis](http://swarmathon.cs.unm.edu/img/LabeledFrontRearChassis.jpg)
 
## 5. Top Plate Assembly

###	3D Printed Parts

Tools:
-	¼” nut driver
-	3/32” hex key

Parts:
-	Top plate
-	GPS/IMU mount
-	Ultrasound tower
-	6x 4-40x5/8” – 3/32” hex key
-	12x #4 washers
- 6x 4-40 nyloc nuts – ¼” nut driver

Below is a picture showing the orientation and placement of the 3D printed parts on the top plate. All of the parts (excluding the camera mount) attach to the top plate using 4-40x5/8” screws and 4-40 nyloc nuts. The NUC base will need only one washer per screw, the other parts will need two. Do not attach the camera mount or the NUC base until after the ultrasound mounts are attached.

![Top Plate Assembly](http://swarmathon.cs.unm.edu/img/TopPlateAssembly.png)
 
###	Ultrasound Sensor Mounting

Tools:
-	Phillips head screw driver
-	1/16" hex key

Parts:
-	6x 4-40x1/2” button head screws – 1/16" hex key
- 3x ultrasound mount kits
-	3x ultrasound sensors

Remove the L-brackets from the ultrasound mount kits. In the picture below, the holes with screws in them need to be drilled out to fit 4-40 screws. A 1/8" drill bit was used for the holes pictured.

Attach the two plastic spacers from the kit using two of the four Philips head machine screws.

![Ultrasound Bracket](http://swarmathon.cs.unm.edu/img/UltrasoundBracket.jpg)

Using the other two Philips head machine screws, screw the ultrasound sensors to the plastic spacers. Below is a picture of a finished ultrasound.

![Ultrasound Mounted](http://swarmathon.cs.unm.edu/img/UltrasoundMounted.jpg)
 
###	NUC Base, Camera, IMU, GPS

Tools:
-	Flat head screw driver
-	¼” nut driver

Parts:
-	4x 4-40x1/2” button head screws – 1/16" hex key
-	4x 4-40x5/8” screws – 3/32” hex key
-	4x #4 washers
- 4x 4-40 nyloc nuts – ¼” nut driver
-	1x 2-56x1/2” nylon screw - flat head screw driver
-	1x GPS
-	1x camera
-	1x IMU
-	Double sided foam tape

Attach the camera mount to the ultrasound tower using four 4-40x1/2” button head screws.

Next, attach the NUC base to the top plate using four 4-40x5/8” screws, four washers, and four nyloc nuts.

Use a strip of double sided foam tap to tape the GPS to the large, flat portion at the bottom of the GPS/IMU mount. Use the 2-56x1/2” nylon screw to attach the IMU to the top area on the GPS/IMU mount.

Use a strip of double sided foam tape to tape the camera to the top of the camera mount. At this point, the top plate should look like the picture below.

![Camera Mounted](http://swarmathon.cs.unm.edu/img/CameraMounted.jpg)

###	PCB, Switch, and Bus Connections

Tools:
-	Flat head screw driver

Parts:
-	PCB
-	Switch
-	Wiring harness
-	4x 2-56x3/8” nylon screws – flat head screw driver

Below is an image of the printed circuit board (PCB), used for connecting all of the Swarmie's electronics. The orientation of the PCB within the NUC base is shown in the same image, with the barrel jack sockets on the back right corner of the NUC base.

![PCB](http://swarmathon.cs.unm.edu/img/PCB.jpg)

Remove all of the nuts and washers from the switch. Feed the switch through the rectangular housing on the rear end of the NUC base, with the label pointing upwards. To get the switch through the housing hole, you may need to straighten the switch, as seen below.

![Switch](http://swarmathon.cs.unm.edu/img/Switch.jpg)

Connect the switch connector to the connector on the PCB labeled "S1" located next to the barrel jack socket which is pointing towards the back of the Swarmie. Screw a single nut onto the switch to secure it in the housing. Then screw a red switch boot onto the switch.

![Mounted PCB](http://swarmathon.cs.unm.edu/img/MountedPCB.jpg)
 
Using four 2-56x3/8” nylon screws, screw the PCB onto the NUC base using the PCB holes labeled on the board as M1, M2, M3 and M4.   
Next, take the A* Microcontroller and plug it into the PCB with the micro-USB socket facing the front of the Swarmie.

Run the multicolored ribbon cable out of the NUC base and under the ultrasound tower.  Connect to the three ultrasound distance sensors, located on the front of the Swarmie, using the three 3-pin headers labeled as "L","C", and "R" with the label facing the front of the Swarmie.  

![Ultrasounds Connected](http://swarmathon.cs.unm.edu/img/UltrasoundsConnected.jpg)

Connect the 4-pin header to the IMU with the label facing outward, as shown in the image below.  The VDD pin on the IMU is not connected to anything.

![IMU Connected](http://swarmathon.cs.unm.edu/img/IMUConnected.jpg)
 
###	NUC Assembly

Tools:
-	Phillips head screw driver

Parts:
-	NUC
-	Wireless module
-	Solid state drive
-	2x RAM sticks

In this section, the wireless module, the solid state drive, and the RAM are installed in the NUC. Unscrew the bottom of the NUC. Unscrew the two screws circled in the image below.

![NUC Open](http://swarmathon.cs.unm.edu/img/NUCOpen.jpg)

Insert the wireless module into the indicated card edge connector, press it down, and fasten it using screw 2 from the image above. You will find a grey and black wire tucked in next to the chassis with gold colored snap-on leads. Plug these into the wireless card with the black wire closer to the chassis of the NUC.  

![NUC Wireless Module](http://swarmathon.cs.unm.edu/img/NUCWirelessModule.jpg)

Next, insert the SSD into the indicated card edge connector and fasten it using screw 1.  Lastly, insert the two RAM sticks into their card edge connectors, on the right in the image above.  These snap in by pressing down.

![NUC RAM and SSD](http://swarmathon.cs.unm.edu/img/NUCRAMSSD.jpg)

The image above shows all parts installed.  The wireless module cannot be seen because it lies beneath the SSD.  Screw the bottom of the NUC back on.

The NUC is attached to the NUC base using two M3x18mm screws which are inserted from the bottom of the NUC base/top plate. The holes are circled in the image below. Use a 2.5mm hex key to fasten the screws. The side of the NUC with the single USB port needs to face the left side of the Swarmie.

!NUC Screw Hole](http://swarmathon.cs.unm.edu/img/NUCScrewHole.jpg)

Plug the GPS and A* Microcontroller into the two adjacent USB ports on the right side of the Swarmie.  Wrap the GPS antenna’s cable, tie it together with a zip-tie, and store the excess cable behind the ultrasound tower.  Wrap the camera’s excess cable around the camera and camera mount, as seen in an image in section 6.3.  Plug the camera into the NUC on the left of the Swarmie.

###	Cover Plate Assembly and Attachment

Tools:
-	¼” nut driver
-	3/32” hex key

Parts:
-	Cover plate
-	4x lid supports
-	GPS Antenna
-	8x 4-40x5/8” screws – 3/32” hex key
-	16x #4 washers
-	8x 4-40 nyloc nuts – ¼” nut driver

Screw the lid supports to the cover plate using the screws listed above, a washer on each side of the screw, and nyloc nuts.  Make sure the screw heads are facing away from the lid supports.  Reference the image below:

![Lid Supports Attached](http://swarmathon.cs.unm.edu/img/LidSupportsAttached.jpg)

Screw the GPS antenna to the GPS and set it aside.

Use the remaining screws, washers, and nuts to fasten the lid supports to the matching holes in the top plate on the Swarmie.  The cutout on the cover plate goes over the camera and the screw heads should face upwards.  

Use double sided foam tape to fasten the antenna to the rear-left side of the cover plate on the Swarmie.  It is important to position it here because the antenna has a strong magnet that may interfere with the compass.  Run the wire from the antenna through the camera cutout on the cover plate.  The following image shows the correct placement on top of the Swarmie.

![GPS Antenna Attached](http://swarmathon.cs.unm.edu/img/GPSAntennaAttached.jpg)

### Top Plate Attachment

Tools:
-	2.0mm hex key

Parts:
-	4x M3x6mm - 2.0mm hex key

Feed the battery connector through the circular hole underneath the PCB. When ready to run the Swarmie, this will need to be plugged into the barrel jack labeled on the PCB as "BATTERY 12V-19V". This is the barrel jack closest to the front of the Swarmie.

Connect the two left motor connectors to the PCB via the two 6-pin headers through the (rear) oval hole underneath the PCB with the RED wire towards the back of the Swarmie.

Connect the two right motor connectors to the PCB via the two 6-pin headers through the (front) oval hole underneath the PCB with the RED wire towards the back of the Swarmie.

Use the following two images to connect the motors to the correct headers.

![Motor Connection Labels](http://swarmathon.cs.unm.edu/img/MotorConnectionLabels.jpg)

![Motors Connected](http://swarmathon.cs.unm.edu/img/MotorsConnected.jpg)

Finally, use four M3x6mm screws to fasten the top plate to the chassis. These are fastened through the four outer holes on the top plate which line up with the holes in the chassis.

## 6.	Fully Assembled

The following are images of the fully assembled Swarmie.

[Note: In this version the antenna is placed incorrectly in the following images.]

![Full Swarmie Front Left](http://swarmathon.cs.unm.edu/img/FullSwarmieFrontLeft.jpg)

![Full Swarmie Front Right](http://swarmathon.cs.unm.edu/img/FullSwarmieFrontRight.jpg)

![Full Swarmie Rear Left](http://swarmathon.cs.unm.edu/img/FullSwarmieRearLeft.jpg)

![Full Swarmie Rear Right](http://swarmathon.cs.unm.edu/img/FullSwarmieRearRight.jpg)

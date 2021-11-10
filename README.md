# DIY-Arduino-based-coil-winding-machine

![image](https://user-images.githubusercontent.com/19898602/141128139-41184e77-0758-4051-86e2-372b6bd74c97.png)


Hello  friends I have made this mini cool looking machine for winding cooper wires.

I have used one numbers of DVD stepper mechanism extracted from old DVD drive of computer

and used one DC motor which is connected via rubber band to the shaft of coiler.

when this DC MOTOR run the coiler will rotate and copper wire start winding on it.

![image](https://user-images.githubusercontent.com/19898602/141128843-0f1c35c5-ffc3-4a63-a8dc-73930bdf89fe.png)

Not all CD/DVD ROM drives have steppers.
Sometimes you will find these also under the term "SLED engine".
What did I learn from this:

In addition to the current-carrying typical cables, broadband cables are also there to conduct signals and close circuits. 
Since these are also soldered to components or the PCB, do not just remove it.

Before you start get an overview of what you are actually looking for 

because I had in advance no overview of what comes to me when disassembling the drives.


# COMPONENT USED

> 1/8 inch (3mm)) thick acrylic sheet

> 3/8 inch (10mm) thick MDF board

> 7/16 inch (12mm) thick wooden board

> 1 no. scrap DVD drive

> 1/8 inch (3mm) shaft

> 13/16 inch (20mm) steel rod

>  3/16 inch (5mm) threaded rods

>  Dupont ribbon cable

> 1 no. 9V DC motor

> 1 no. 0.96 OLED display

> 1 no. rotary encoder

> 1 no. IR sensor

> 26 AWG copper wire

> Rubber belt

> Various 3D printed gears and wool spools, etc

> 3 no. 693 zz ball bearings

> 2 no. NEMA 17 stepper motor

> 1 no. custom PCB board 

> 2 no. A4988 stepper driver

> 1 no. Arduino Nano

> 1 no. L293D 16-pin IC stepper motor driver controller

> M6 X 40 bolts

> Various bolts and nuts and acorn cap nuts. 


Right, now to get on with the build. Hold on tight, there is a lot to get through.

The basic concept of the machine is to create a smaller spool of copper wire from a larger one automatically. A rotary dial is used to select the number of turns of the wire you want, which displays on the OLED display. 

Once set, the machine gets to work in short order.

The first step is to dismantle that old DVD drive you've managed to salvage. You are after the DVD laser head assembly inside. 

![image](https://user-images.githubusercontent.com/19898602/141129530-61a3bd5a-5017-45fc-bda3-fc936b32bb79.png)


With that piece isolated, strip and solder the stepper motor terminals to the appropriate contacts on the salvaging DVD player's optical laser head's motor. This will vary depending on the design of the DVD player in question. 

![image](https://user-images.githubusercontent.com/19898602/141129569-fd0a057a-189a-4250-9428-c7a303d49c18.png)


Strip off the part you don't need (basically the optical pickup) and make room for the wire guider you will build later. Watch the video for more details on this part. 

Next up, take the bolt and file flat the topmost part of two opposite sides. This will be used to make the wire guider later on.  

![image](https://user-images.githubusercontent.com/19898602/141129610-b2ed9f98-7c14-46d7-8f71-3b6482ee1eb7.png)


Then drill a hole in the center to guide the copper wire between the spools. Bevel the hole, if required. 

![image](https://user-images.githubusercontent.com/19898602/141129659-8a5c0da4-2869-40b8-af06-910f6754c97c.png)


![image](https://user-images.githubusercontent.com/19898602/141129679-3e19c451-e30d-4cc1-8614-9372ee63351c.png)


Now insert the wire guider into the middle of the former DVD laser head assembly. Use a bolt to secure it into place. 

![image](https://user-images.githubusercontent.com/19898602/141129712-8db3f775-1377-47d3-b76f-d6a848e6a63e.png)


Next, take some random plastic pieces, or 3D print them to design. Make, or include in the design, an off-center 5/16 inch (8mm) hole. It will need to be deep enough to hold three 693 ZZ bearings when complete.

Drill and tap one of the sides too, as shown in the video. You will need two identical pieces later. If required, cut down to the final shape. 

Again watch the video for more detailed instructions on this section as it will depend on what you get your hands on. 

Insert 3 no. ball bearings into the hole. 

![image](https://user-images.githubusercontent.com/19898602/141129774-4148a0cd-5911-497e-97b5-b5edc03d2f35.png)


Test it by Inserting the 1/8 inch (3mm) shaft through the eyes of the ball bearings. This will hold the bobbin for the copper wire later on. 

Now take the 13/16 inch (20 mm) aluminum rod. We are now going to machine the pully and bobbin gripper parts of the machine. 

Secure into a vice, and drill holes into it as shown in the video, This make take some trial and error. They will need to be M3 size, and tapped, and will be used for the locking nuts. 


![image](https://user-images.githubusercontent.com/19898602/141129826-4909a2d7-0a7a-415c-8772-85f0e8608db3.png)



Machine into shape, as shown in the video. DrilL A 1/8 inch (3mm) hole into the end to fit on the 1/8 inch (3mm) shaft used earlier. Further machine and part-off the finished piece, as shown in the video. 

You will also need to make a pulley piece to hold the rubber band. This will be used to turn the bobbin using the DC motor later. 


![image](https://user-images.githubusercontent.com/19898602/141129872-9a37ff2b-8614-4ab3-a15e-030f7200868f.png)


Now assemble the gripper and pulley assembly. 
Now scavenge some more pieces from the DVD player to built a holder for the DC motor. The process, and dimensions, will vary depending on the DVD player design. 

Watch the video for more details on this stage. 


Attach the motor assembly to the DVD laser head assembly frame as shown in the video. Also, attach the bobbin gripper assembly in a similar fashion. 

Now take the M5 threaded rods. These will be used to make the legs to hold the assembly in place. 

![image](https://user-images.githubusercontent.com/19898602/141129949-4a12f3bb-313b-43d5-8516-5f0431ff0dd7.png)

![image](https://user-images.githubusercontent.com/19898602/141129989-acb2ac45-f746-46c3-af39-ebb7fe3b2348.png)

Next, we will make the display and knob mounting. Take the acrylic sheet and cut to size, as shown in the video. 

Drill holes and cut in notches as also shown in the video. You may want to mock this up before committing to cutting the acrylic sheet.

Heat and bend it to the desired angle. 

Now take the IR sensor. This will be used to count the number of turns of the bobbin.

Create a suitably sized, and shaped, mounting for it, and attached the appropriate place on the ex-DVD player's main assembly. 

![image](https://user-images.githubusercontent.com/19898602/141130084-1c1cb633-baf4-442a-b806-a52ad7c5c468.png)

# CUSTOM PCB

![image](https://user-images.githubusercontent.com/19898602/129939820-49442e93-d356-4228-86be-c789daaae4a2.png)


![image](https://user-images.githubusercontent.com/19898602/125588570-5cc527d3-79ea-40f4-8323-70093eb0e1d6.png)


![image](https://user-images.githubusercontent.com/19898602/125588592-7213d3f4-ddb1-425a-ad33-9f070ff8d8a1.png)


L293D = 2 pieces


LM7809 = 1 piece


LM7805 = 1 piece


10.1uF electrolytic = 1 piece


1N5408 = 1 piece


1N4007 = 1 piece


led = 1 piece


resistance of at least 470 Ohm = 1 piece




Arduino Nano = 1 piece


Oled display = 1 piece


Encoder = 1 piece


A4988 controller = 2 pieces




socket 8 + 8 = 1 piece


PCB female pin header connectors


screw connectors for printed circuit boards


I have designe a PCB which is multipurpose and order it from [JLCPCB](https://jlcpcb.com/IAT ) 

I always prefer [JLCPCB.com](https://jlcpcb.com/IAT) for my PCB needs, [JLCPCB.com](https://jlcpcb.com/IAT) have best deals for their customers
$2 for 1-4 Layer PCBs, free SMT assembly monthly.


and this is not it if you are new customer for [JLCPCB.com](https://jlcpcb.com/IAT) you will get 18$ coupon on your
first registration to their site its limited period offer so what are waiting for go  and get your benefit. 


[Click here to visit JLCPCB.com](https://jlcpcb.com/IAT)

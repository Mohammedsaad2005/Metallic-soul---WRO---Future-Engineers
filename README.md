# Metallic Soul


The Metallic soul is a Self Driving bot which is programmed to drive autonomously and avoid obstacles with the use of sensors and motors present in the LEGO Mindstorm EV3 kit.



**TEAM DETAILS:**

Team name: Metallic soul 

Country: United Arab Emirates

Member 1 : _Fahad_

Member 2 : _Abdulla Abdul Jaleel_

Member 3 : _Mohammed Saad_

Coach : Nandini Kurmude



**ENGINEERING MATERIALS:**

Lego Mindstorms EV3 is the third generation robotics kit in Lego's Mindstorms line. It is the successor to the second generation Lego Mindstorms NXT kit. The "EV" designation refers to the "evolution" of the Mindstorms product line. "3" refers to the fact that it is the third generation of computer modules - first was the RCX and the second is the NXT. It was officially announced on January 4, 2013 and was released in stores on September 1, 2013. The education edition was released on August 1, 2013.

This repository contains engineering materials of the autonomous driving bot participating in the WRO Future Engineers competition in the season 2022.


**CONTENTS:**

- t-photos: contains 2 photos of the team (an official one and one funny photo with all team members)
- v-photos: contains 6 photos of the vehicle (from every side, from top and bottom)
video contains the video.md file with the link to a video where driving demonstration exists
- schemes: contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
- src: contains code of control software for all components which were programmed to participate in the competition




**Team photos:**


**Funny photo:**

![Funny photo](https://user-images.githubusercontent.com/106605597/171986106-39b33931-7373-49c3-a1f7-7019471ab654.jpg)



**Official Photo:**

![official photo](https://user-images.githubusercontent.com/106605597/171985665-afa270d7-2e3e-40b3-81e7-ebe3732f89c9.jpg)

'''
'''

#Vehicle photos:

Below are the 6 faces of the self driving autonomous vehicle.



1. FRONT FACE:


![Front](https://user-images.githubusercontent.com/106605597/171985618-d10bbbb0-6ed3-4f0c-9a4e-24c42e480f57.jpg)





2. BACK FACE:


![Back](https://user-images.githubusercontent.com/106605597/171985622-00911b8e-c569-4910-acb1-80c78cb98921.jpg)




3.RIGHT FACE:


![Right](https://user-images.githubusercontent.com/106605597/171985626-d2238f69-94c9-434d-ad25-b8ca4634f66b.jpg)


4.LEFT FACE:


![Left](https://user-images.githubusercontent.com/106605597/171985636-eb40632f-a258-4eca-8703-02d842604d96.jpg)


5.TOP FACE:


![Top](https://user-images.githubusercontent.com/106605597/171985641-c16afab8-0f16-40b5-8c82-6470ef7b5496.jpg)



6.BOTTOM FACE:


![Bottom](https://user-images.githubusercontent.com/106605597/171985415-8b2c4bce-6eb1-4490-9353-44a4316e7bd6.jpg)


#Link to YouTube video:

https://youtu.be/EYeG8PGeubc


#CODES:


![EV3 coding](https://user-images.githubusercontent.com/106605597/171990242-778b78c4-88b6-4c07-a625-af671fe108b5.PNG)



#SCHEMATIC DIAGRAM:

Below is a schematic diagramatic representation consisting of all the electromechanical components (sensors, motors, bricks, etc) used in building the Autonomous driving bot.

![p1g4k27vf51gmih7ciqu7n71cah4-0](https://user-images.githubusercontent.com/106605597/171986214-d30a4e59-0fa3-4094-a144-681bab781eca.png)

![diagram](https://user-images.githubusercontent.com/106605597/171990257-c2736470-7228-45f7-80e7-199d0f73fa4f.PNG)




#INTRODUCTION:

''''

#ELECTROMECHANICAL COMPONENTS:

The Metallic Soul Atonomous bot is built using the Lego EV3 Mindstorm's robotics kit. The brief description of each electromechanical component (sesors, motors and bricks) used in building this robot are given as folllows in order to understand the code and functionality of each component better.


#I.Sensors:


**1. ULTRASONIC SENSOR:**

The ultrasonic sensor is primarily used for the detection of obstacles and their avoidance. It is attached to the front of the robot. The digital EV3 Ultrasonic Sensor generates sound waves and reads their echoes to detect and measure distance from objects. It can also send single sound waves to work as sonar or listen for a sound wave that triggers the start of a program. We have used it to detect the distance of the approaching obstacle and drive automously according to the situation.  

![41hJmhLR4BL _AC_SY1000_](https://user-images.githubusercontent.com/106700080/171618265-43b1c080-d371-4ac1-9feb-b000296bd986.jpg)


**2. COLOUR SENSOR: **

The colour sensor has three different modes: colour, reflected light intensity, and ambient light intensity.

Colour – In this mode, the colour sensor can differentiate up to seven different colours: black, blue, green, yellow, red, white, and brown. Each colour is also represented by a value (see “Colour and light data table” below). Note: For best results, the colour sensor needs to be 1-2 cm away from the colour you are trying to detect, and have consistent lighting.
Reflected light intensity – In this mode, the colour sensor emits a red light and measures the amount reflected back into itself from the surface you are testing. The intensity of the light is measured as a percentage from 0 to 100, with 0 being very dark, and 100 being very bright.
Ambient light intensity –  In this mode, the colour sensor measures the amount of light in its environment, without producing its own light source. Ambient light intensity is measured as a percentage from 0 to 100, with 0 being very dark, and 100 being very bright.The colour sensors are used to detect change or for the comparison between two or more different colour. Two colour sensors were used, one placed facing downwards and the other front faced.

![download](https://user-images.githubusercontent.com/106700080/171618191-b636c9c8-94b7-4363-9ae2-d9a7b86a09f2.jpg)


**3. GYRO SENSOR:**

The gyro sensor helps in detecting the rate of rotations by measuring the angles. It is placed left to the brick lower body in our robot to assist it in rotations. The gyro sensor detects rotational motion in the plane indicated by the arrows on the top of the sensor housing. The sensor measures the rate of rotation in degrees per second and keeps track of the total angle of rotation in degrees.
 
![s-l400](https://user-images.githubusercontent.com/106700080/171618289-50a9ef1e-dc7c-480c-9856-3cfcf4e04c1b.jpg)







#II.Motors:


**1. LARGE MOTOR:**

The large motor is the primary driving base of our self driving robot. It has an built-in rotation sensor (with 1- degree resolution), The large motor is optimized to be the driving base on our robot. The large motor runs at 160 - 170 rpm, with a running torque of 20 Ncm and a stall torque of 40 Ncm.  It is slower but indeed very stronger .

By using the Large motor we are able to run our car with greater efficency and accuracy.
 
![31pFKiNKOsL _SR600,315_PIWhiteStrip,BottomLeft,0,35_SCLZZZZZZZ_FMpng_BG255,255,255](https://user-images.githubusercontent.com/106700080/171618600-5f5aad46-61b2-42a4-9594-879acbe34768.png)


**2. MEDIUM MOTOR:**

The medium motor also includes an built-in rotation sensor (with 1- degree resolution), But it is smaller and lighter than the large motor , which implies that it is able to respond more quickly than the the large motor. The large motor is optimized to be the steering motor on our autonmous driving robot.

![download](https://user-images.githubusercontent.com/106700080/171618669-6ac5cc2a-c0d2-428c-b813-914db39861fd.jpg)




#II.Brick:

The brain of our robot, the Lego Mindstorms EV3 intelligent brick gathers informations coming from the sensors, processes it and sends commands to the motors for an efficient and amazing autonomous ride.

This programmable, intelligent brick serves as the heart and brain of LEGO® MINDSTORMS® Education EV3 robots. It features an illuminated six-button interface that changes color to indicate the brick's active state, a high-resolution black and white display, built-in speaker, USB port, a mini SD card reader, four input ports and four output ports. The brick also supports USB, Bluetooth and Wi-Fi communication with a computer and has a programming interface that enables programming and data logging directly onto the brick. It is compatible with mobile devices and is powered by AA batteries or the EV3 Rechargeable DC Battery. 

On-brick programming and datalogging that can be uploaded into the EV3 software

Computer-to-brick communication through on-board USB, or external Wi-Fi or Bluetooth dongles

USB 2.0 host enabling bricks to be linked in a daisy chain, allows Wi-Fi communication and connection to USB memory sticks

Powered by six AA batteries or the 2050 mAh lithium ion EV3 Rechargeable DC Battery

The EV3 Brick is the primary component of our robot. It supplies power to the robot and controls all its movements and actions. It is the part which stores all the programs neccessary for the functioning of the robot. It consists of 4 buttons, i.e power/OK button, off button, left and right, all of which help in assisting the robot in its movement. 

![95646c01](https://user-images.githubusercontent.com/106700080/171619375-7eee289d-01fd-4aba-97f0-a269a7bf2e48.png)

#CODING:

The programming platform used for the coding of the self driving Metallic Soul robot is Lego Mindstorm Education EV3.

Learning outcome : 







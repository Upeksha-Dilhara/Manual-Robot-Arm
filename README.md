# Manual-Robot-Manipulator
This robot arm was developed as group project with my colleagues who are Hiruna, Nimesh, Ramitha and myself. This is first robot arm I have contributed in my dream passion. We made the prototype of our design which is controlled by user manually.   

## Specification of the arm
- Six degree of freedom is achieved by using six joints in the arm.
- End effector is gripper which can pick and place an object.
- ESP32 cam module is used at end effecter to find the object 
- Arm can be controlled from any where else by using the feedback of the cam module which gives feedback to user’s device through the Wi-Fi.
-  There is controller panel with six controllers 

## Components and Modules Used
### Motors 
We used 5 servo motors and 1 stepper motor for the six joints.
- SG90 servo - end effector(gripper).
- Two MG90S Metal Gear motors and – Connect the middle links 
- 40Kg High Speed servo Metal Gear motors -Connect the middle links
- Nema17 Stepper Motor – Base Joint

![motors](https://github.com/Upeksha-Dilhara/Manual-Robot-Arm/assets/128304167/0a6f9660-51f2-477b-8905-7bf659530700)



### Power supply

We found that when all the motors are working, the motors are driven about 5A current, because all the motors are at stall toque expect stepper motor. Therefore 10A power supply was designed by one of group member Nimesh. Output voltage of power supply is 12V.

![WhatsApp Image 2023-09-19 at 19 33 21](https://github.com/Upeksha-Dilhara/Manual-Robot-Arm/assets/128304167/36821746-2e12-4ab3-a453-844913631e4c)

### Controlling Circuit 

Atmega328p was used as microcontroller. There six potential meters to control each motor separately. All the servo motors were controlled by PWM signals as usual. 

12V Output of the power supply is given to 5V buck convertor which powered microcontroller and some servo motors. 

We used ESP32 cam module which can be connected to any device through the Wi-Fi at end effector. The purpose of using a cam module was user can be controlled the arm by observing output of cam module. Because user can see what the end effector orientation and position is. 

##


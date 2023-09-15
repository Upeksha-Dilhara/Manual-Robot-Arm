# Manual-Robot-Arm
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


### Micro controller 
Atmega328p was programmed for controlling the motors.

### Power supply

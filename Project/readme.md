# Floor cleaner

# Description
* Automatic floor cleaner is a system that enables cleaning of the floor by the help of highly stabilized and rapidly functionalized electronic and mechanical control system. 
Current project work targets to use automatic floor cleaner for large floor in house-hold purposes and office floors.This can be used on flat surfaces for cleaning
# In Action
![automatic-vacuum-cleaner-robot-project-block](https://user-images.githubusercontent.com/99128901/155833436-de4a2bcc-fcd5-441f-a97c-8a65e9463a6d.png)
# Block Diagram
![BD_FC](https://user-images.githubusercontent.com/98872185/155708471-750a3503-6801-48c5-baf5-fc89f11b81ea.PNG)

# Flowchart
![FF2](https://user-images.githubusercontent.com/98872185/155760065-22b28913-d386-4de7-980d-0b21674bb88b.PNG)


# V-Model design
![v_model](https://user-images.githubusercontent.com/98872185/154843619-51f6a8b5-bf05-4366-bcbe-94ac0f084d1f.PNG)


# Components used

* This design consists of Arduino controller, Motor Driver, DC motor, Ultrasonic sensor, IR Proximity sensor, Vacuum pump.

## Ardunino UNO
* Arduino UNO is a microcontroller board which has ATmega328 from the AVR family which controlls the all process to be carried out in the system.
* There are 14 digital input/output pins, 6 Analog pins, a 16 MHz ceramic resonator, USB connection, power jack, and also  has a  reset button. 
* Its software supported  by  a number  of libraries  that makes the programming easier.

## Motor Driver
* L293D is a Motor Driver IC which is used to connect the motor with the microcontroller and provide them  sufficient voltage supply to the design. 
* L293D has  16-pins in  which 4  are input  pins, 4  are output pins, 2 are enable pin, 4 GND pins and 2 pins for power supply.  It is used to control  DC motors simultaneously to rotate the bot in any direction. 
* It works according to the concept of H-bridge. The voltage has to change its direction to rotate the motor in clockwise or anticlockwise direction.

## DC Motors
* A simple DC motor is used to control the rotation of the machine.
* It converts the electrical energy to the mechanical energy and is connected with the wheels of the cleaner to move it in all directions. 

## Ultrasonic sensor
* Ultrasonic sensors are implemented to calculate
the distance between the obstacle and the system. 
* In order to detect the edges and to avoid obstacles, ultrasonic sensors
are mounted on front, right and left side of wheels.
* It  transmits  ultrasonic waves  and receives  the reflected  waves  and measures  the distance  to the  target  by computing  the  time between  the emission and reception. 
* For measuring the distance: 
Distance= ½ (speed of sound * time taken)

## IR Proximity Sensor
* IR sensors are object or obstacle detection infront of sensor.
* It has an IR LED and a photodiode, the IR LED emits IR light and if any obstacle comes in front of this emitted light, it will be reflected, and the reflected light will be detected by the photodiode. 
* The generated voltage from the reflection will be very low. 
* An IR module has three pins - Vcc, ground, and output. Usually, the output goes low when an obstacle comes in front of the sensor

## Voltage Reguator(LM7805)
* It is a 3-terminal voltage regulator that outputs any voltage to +5V.
* In this design it converts the 7.4V from battery to 5V.

## Vacuum Pump
* For Cleaning purpose  vacuum pump is used instead of conventional blower fans, resulting in higher suction power, leading to shorter cleaning time with better cleaning results. 
* The powerful suction thus generated enables to pick metal chips, garbage, paper pieces, dust particles.



# System Design
1) Path sensing unit.
2) Distance calculation.
3) Robotic movement.
4) Straicase detection.
5) Suction unit.

# Sub-system Design
1) Direction control by ultrasonic sensor.
2) Communication through ultrasonic waves.
3) Calculation of travelling duration.
4) Various movement patterns.
5) Avoid bot falling from stairs.
6) Vacuum suction of particles.



# Identifying Features
* Avoiding obstacles and path sensing using ultrasonic sesnor.
* Cleans the unwanted particles like dust,sand.
* Falling from stairs can be avoided by IR proximity sensor.
* Calculates the distance .

# Abstract
Automatic floor cleaner is a compact robotics system which provides floor cleaning service in
room and big offices reducing human labor. Basically as a robot it eliminates human error and
provide cleaning activity with much more efficiency. Also due to manual labor
involved this is time consuming and irritating to clean the floor. Also in big offices floor area is
very huge and the people involved there for cleaning purpose cannot clean it much more
efficiently. This is where the robot comes as an advantage. Also the robot is small and compact
in size.

## High level requirements
| ld | Description | Category |
| --- | --- | --- |
| HL1 | Senses path using ultrasonic sensor | done|
| HL2 | Calculating the obstacle distance | simulation|
| HL3 | Movement of the bot | to be done |
| HL4 | Staircase detection using IR sensor | in simulation |

## Low level requirements
| ld | Description | Category |
| --- | --- | --- |
| LL1 | With Ultrasonic it can be done in three directions. (Left, right, Front) | Technical |
| LL2 | To send and receive the ultrasonic waves | Technical |
| LL3 | Calculating the distance travelled by ultrasonic waves and multiplying the duration by 0.034 | Technical |
| LL4 | Various movement patterns based on obstacle | Technical |

# Applications of Vacuum cleaner

  Garment steamers 
  Household products(Pillows, and Carpets)
  Air purifier; Air Education1) Freshen Upholstery.

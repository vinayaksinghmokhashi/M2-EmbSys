# TWO WHEELED BALANCING ROBOT AS AN EMBEDDED SYSTEM

## 1.	Abstract and Problem description

 Two- wheeled self balancing robot is designed using the concepts of embedded system design. This embedded system is an assembly of various sensors and actuators with Arduino as a processing unit. It is automatic that carries a payload from source location to the destination according to user commands by balancing itself based on sensory inputs.



## 2.	Requirements: 


### Requirement design and analyzes of customer needs


## 2.1	High level requirements:


| Test ID | Description | Category | Status |
|---------|-------------|----------|--------|
|HLR_01|The robot shall expected to transport a payload from one Location to another.| Functional | To be implemented |
|HLR_02| The robot shall expected to balance itself and also the payload while working.|Functional | To be implemented |
|HLR_03| The robot shall balance itself from sudden obstacle.| Functional | To be implemented |
|HLR_04| The robot shall expected to calculate the torque required. | Functional | To be implemented |
|HLR_05| The robot shall expected to calculate the torque and speed required to balance itself. | Technical | To be implemented |



## 2.2 Low level requirements:


| Test ID | Description | HLR_id | Status |
|---------|-------------|--------|--------|
| LLR_01 | The robot shall be receiving the source and destination location from user   | HLR_01 | To be implemented |
| LLR_O2 |  The robot shall be employing its wheels connected to DC motor to achive its goal | HLR_01  | To be implemented |
| LLR_03 | The robot shall be carrying load on it throughout the entire process  | HLR_01  | To be implemented |
| LLR_04 | The robot shall be incorporated with sensors like accelerometer and gyroscope or combination of both inorder to achive the high level requirement 2  | HLR_02   | To be implemented | 
| LLR_05 | The robot shall be employing the perceived sensory information balance itself and payload  | HLR_02  | To be implemented |
| LLR_06 | The robot shall be able to sense the loci of itself and act upon the sudden obstacle found in its way avoid it by acting on sensory input  | HLR_03   | To be implemented | 
| LLR_07 | The robot shall be able to process the sensory input and calculate the required torque to balance itself and to move in its way  |HLR_04   | To be implemented | 
| LLR_08 | The robot shall be able to decide the speed required for the motion based on the torque calculated  | HLR_5  | To be implemented |



## 3. Components used:

|SL No | Component | Description|
|------|-----------|------------|
| 1. | Arduino Uno | Arduino Uno is a microcontroller board based on the ATmega328P family. It has total 14 digital input/output pins (of which 6 can be used as a PWM outputs), 6 analog inputs pins, a 16 MHz ceramic resonator, an USB connection,  power jack, an ICSP header and a reset button.  |
| 2. | MPU 6050 | The MPU6050 consists of a 3-axis Accelerometer and 3-axis Gyroscope. Which measure acceleration, velocity, orientation, displacement and many other parametrs |
| 3. | DC Motors | It uses a stationary set of magnets in the stator, and a coil of wire with a current running through it in order to generate an electromagnetic field which is aligned with the centre of the coil. |
| 4. |  L293D Driver | The L293D is a 16-Pin Motor Driver IC. it is mainly used to drive the motors. A single L293D IC which is capable of running two DC motors at once and also the direction of these two motors can be controlled |
| 5.| 16x2 LCD |  The term LCD stands for liquid crystal display. It is one kind of electronic display module used in an extensive range of applications like various circuits & devices like mobile phones, calculators, computers, TV sets, etc. These displays are mainly preferred for multi-segment light-emitting diodes and seven segments. The main benefits of using this module are inexpensive. |
| 6. | 10 Ohm Potentiometer|  a single turn 10k Potentiometer has a rotating knob.. These three-terminal devices can be used to vary the resistance between 0 to 10k ohms by simply rotating the knob.|

## 4. SWOT Analyzes:

![Screenshot from 2022-02-25 22-37-19](https://user-images.githubusercontent.com/98843684/155757581-2c266b12-3588-41f6-b09d-81a004a3c250.png)

## 5. 5 W's and 1 H:

![Untitled](https://user-images.githubusercontent.com/98843684/155759301-6e9c138b-fa66-43b0-af22-87c89a57f155.png)

## 6. Applications:

Two wheeled balancing robots use a “closed-loop feedback control” system. Which means that real-time data from motion sensors is used to control the motors and quickly compensate for any tilting or imbalance in  motion in order to keep the robot upright. Similar self-balancing feedback control systems can be seen in many other applications in day to day life. Some of the examples include:
 Segways
 bipedal robots
 space rockets
etc.




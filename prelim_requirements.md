# Requirement Analysis Document

The final product is to be a module with the following features:

1. Wifi/BT Communication
2. 
3. Four degrees of freedom
4. Connection to camera
5. Send Camera input
6. LEDs to display when board on/off

Preliminary Function List:
1. 3 Motor control functions
2. Connection to a servo driver
3. Wifi Communication
  a. Send and Recieve data
3. Task Scheduler (if using RTOS) --> not sure how this changes for Linux
4. Connection to Camera

Preliminary Software Requirements:
1. Connections between camera and processor
2. Connections between servo drivers and processors
3. Connection between main control unit and board
4. Motor control functions

Preliminary Hardware Requirements (based on old schematic):
1. STM Processor
2. 4 motors
3. Step Regulator
4. Switching regulator
5. Wifi Module
6. 2 servo drivers
7. USB interface
8. LEDs


Questions:
1. How can I determine how much processing is needed on board?
2. What exactly is the module doing (i.e., what is the final project section missing)?
3. How detailed of a flowchart is needed?
4. What processor will we be using? This determines the hardware needed.
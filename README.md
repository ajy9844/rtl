RTL (RIGHT-TURN TRAFFIC LIGHT)π₯
==============================
The RTL embedded system is a two-way signal system between drivers and pedestrians to prevent right turn accidents at intersections.
The system is smart transportation system based on Raspberry-Pie and uses ultrasonic sensors and pressure sensors.
The ultrasonic sensor informs the pedestrian that there is a vehicle turning right and the pressure sensor informs the driver that there is a pedestrian.  
For more information see the [documents](./μμ€ν_νλ‘κ·Έλλ°_μ μμ_ν7_ASP_.pdf).  

Requirements
------------
- Raspbian OS  
- gcc (Gnu C Compiler)

Quick Start
-----------
To execute the program, three raspberry pies are required!
#### Server1
```
gcc -o server1 server1.c -lpthread 
./server1
```
#### Server2
```
/* use 'make' command to compile */
make
./server2.out
```
#### Client
```
gcc βo client client.c -lpthread
./client
```

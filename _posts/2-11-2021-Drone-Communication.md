---
title: Drone Communication
date: 2021-11-2
---
Commands to communicate with a drone can be sent across a wireless network using an IP Adressto tell a drone how to navigate using preset constants that can be 
found in the dronesAPI. These commands allow you to do a multitude of this moving in all 6 degrees of freedom with the drone, the commands are sent to the drone 
from the ground control computer using UDP packets. UDP is used as it sends command to the drone and responces back in real time, which allows the pilot to react a 
lot faster thanif the were using TCP. 

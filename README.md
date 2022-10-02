# IBM-Project-42091-1660649253
Real-Time River Water Quality Monitoring and Control System
Assignment 1: https://www.tinkercad.com/things/cH72arjRDU1-light-on-based-on-ldr-and-pir-/editel


Assignment -2
Code:

import random,time
while 1:
    temp = random.randint(-20,50);
    humidity = temp = random.randint(0,100);
    if(temp>35):
        print("High Temperature")
    if(temp<35):
        print("Normal Temperature")
    time.sleep(1)

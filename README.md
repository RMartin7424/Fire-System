# Fire-System
These files are used with the Raspberry Pi to create a fire detection system. 

As a part of a class project my team used a raspberry pi, temperature reader, an alarm, and a button to create a system to detect fires. The core of the project can be found in the Console.sh file that calls the temp.py file to check the temperature. When it is a temperature greater than 130 it checks the nearby pi for a high temperature and will record the temperature and sound the alarm if both detect high temperatures. 


Files

AdafruitDHT.py - This file is where the original code to retrieve the temperature came from.
Console.sh - This file contains the core of the code, it's where the hardware is activated and the fire sytem runs.
Temp.py - This file is used to retrive the temperature from the surrounding area.
FireHis.log - When a high temperature is detected it is recorded here.
Adafruit - Help file for AdafruitDHT.py
Console - Help file for Console.sh
Log - Help file for FireHis.log
Temp - Help file for Temp.py

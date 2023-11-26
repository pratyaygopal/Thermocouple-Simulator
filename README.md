# Thermocouple-Simulator
**Documentation for my project for my Internship**

Requirements:
* Raspberry Pi 3
* PCF 8591 DAC/ADC IC
* MCP4725 DAC IC (not used)

Purpose:
To create a cheap yet accurate thermocouple simulator to replace the expensive 8 channel ones which are currently used to calibrate the low temp cryo units.

INSTALL PYTHON LIBRARIES ON RPI USING:
* sudo pip3 install pillow
* sudo pip3 install numpy
* sudo apt-get install libopenjp2-7
* sudo apt install libtiff
* sudo apt install libtiff5
* sudo apt-get install libatlas-base-dev

FOR PYTHON 2:
* sudo apt-get update
* sudo apt-get install python-pip
* sudo pip install RPi.GPIO
* sudo pip install smbus

FOR PYTHON 3:
* sudo apt-get update
* sudo apt-get install python3-pip
* sudo pip3 install RPi.GPIO
* sudo pip3 install smbus

ACCESSING THE MACHINE: 

The raspberry pi and the machine used to access it must be on the same network. 
For initial setup plug raspberry pi into the monitor and type in ifconfig in the terminal. 
This will give us the ip address of the raspberry pi on the local network. 
Open your access machine and use putty to ssh into that ip. 
After establishing a connection login as :
user : pi
pasword : raspberry

Now depending on the folder the script is in type in cd <Folder Path>.
If you are not sure, use ls to list all the files in the current folder.
Now run the script using python ./<Script_Name>

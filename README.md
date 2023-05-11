# Smart-Home-Prototype

## Group Members:
Sanidhya S. Johri(B20CS061)
Sawan SanjayKumar Patel (B20CS063)


## Problem Statement:
Creating an IoT based app to interact with any home electrical equipment.


## Design and Implementation:

Hardware:
For the project purpose, we decided to create a prototype of the idea. Hence we used an LED 
as the electrical appliance which was to be used. We also used HC05 bluetooth module along 
with an arduino board. The bluetooth sensor was fed as input to arduino and an output from 
arduino was fed to the LED.

Software:
We used flutter for creating the app for the project. The reason for choosing flutter is it 
provides convenience in both android and ios based devices. 
Whenever ON/OFF switch is pressed, an interrupt is sent to the bluretooth sensor, which in 
turn triggers the output of arduino’s output pin to glow the LED.



## Working:
The app has an “Enable Bluetooth” toggle switch which used to turn ON and OFF the 
bluetooth in the device or mobile. Once the bluetooth is turned ON, we select the bluetooth 
device from the dropdown under “PAIRED DEVICES”. Once the device (which is sensor in 
our case) is selected, we turn it ON/OFF from the widget named “DEVICE x”.


## Dependencies:
Flutter Bluetooth

## Hardware Devices Used:
Adruino Uno
Jumper Cables
Bluetooth sensor
LED


How to run the project:
Scan the QR code in the image provided along with the project and you will get the link to the apk file to run on the device.
Download and install the file, providing you with the apk to control the hardware device.

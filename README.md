# Client-Server-Tracker
Client and server scripts to run an object tracker with OpenCV, a Pi Camera and Pan and Tilt with 9g servos controlled by remote GPIO.

## Dependencies
Be sure to have OpenCV fully installed on your computer before running server script on it. 

	sudo apt-get install python-pip
	pip install picamera
	pip install imutils
	wget https://raw.githubusercontent.com/ivmech/ivPID/master/PID.py
	pip install RPi.GPIO
	pip install socket
	pip install pil

## Start Guide
Firstly, run server_script on your computer.

Secondly, run client_script on Raspberry Pi. NOTE: Remember to specify the correct server address.

Finally, select an object to track on "Stream" window and let the system do the rest :)

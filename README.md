# lamp_for_Jenkins
It's script for using physical led lamp with Jenkins. 
It was created for visual displaying of building process on Jenkins.
When somebody starting of building, lamp is turn ON. When building is ended, lamp is turn OFF.

This device based on Python + Arduino + pyFirmata.

pyFirmata - it's a Python interface for the Firmata protocol. 
Firmata is a generic protocol for communicating with microcontrollers from software on a host computer.


What we need for repeting of device? 
1. Python or other language (Wich has libs for Firmata protocol).
2. Any arduino board with firmware of Firmata. 
(look at this tutirial: http://www.instructables.com/id/Arduino-Installing-Standard-Firmata/)

And that's all!

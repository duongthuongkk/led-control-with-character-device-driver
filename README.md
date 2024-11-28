# led-control-with-character-device-driver

## Description
This is a kernel module which creates a simple character device driver to control a LED in Beaglebone Black

## Features
- Design a simple kernel module to control LED and port it on Beaglebone Black. 
- This kernel module will load a simple character device driver to control GPIO30.
- Build a Linux app running on the terminal to collect requests from the user.
- User space sends data to kernel space by a syscall named "ioctl".

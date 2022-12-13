## CNC Machine Description

This personal project was an idea that I had about a machine that could visually detect objects and draw,
carve, or paint them in various materials.

The machine moves in the x, y, and z coordinates using 3 stepper motors and 1 router. 
There are 3 stepper motor drivers that are connected to 2 power supply boxes. 
The stepper motor drivers are controlled by a Raspberry Pi mini computer using C. 

One of the functions of the machine relies in using a program that was written in Java.
This Java program, can be given an image as input and the program returns data in a text file format
that contains coordinate points of the outlines of the objects in the image.

This data is in turn fed to the Raspberry Pi and a C program that takes this data to control the stepper motors
and either carve or cut the shapes into different materials such as plastic, wood, metal, and so forth.

The machine is in the prototype stage and can be modified for various other uses, including lasers, and inks.

## CNC Machine

https://user-images.githubusercontent.com/86565212/207436392-1a6df2d7-1b7a-48c3-8320-8335248c3f45.mp4


## CNC Machine Description

This personal project came about from an idea about a machine that could visually detect objects and carve, or
cut them on various materials.

The machine moves in the x, y, and z axes using 3 stepper motors and 1 router.
There are 3 stepper motor drivers that are connected to 2 power supply boxes.
The stepper motor drivers are controlled by a Raspberry Pi minicomputer using C.

One of the functions of the machine relies on using a program that was written in Java.
This Java program can be given an image as input and the program returns data in a text file format
that contains coordinate points of the outlines of the objects in the image.

This data is in turn fed to the Raspberry Pi to control the stepper motors 
and either carve or cut the shapes into different materials such as plastic, wood, metal, and so forth.

The machine is in the prototype stage and can be modified for various other uses, including lasers.

## CNC Machine

* Images

![Working](https://user-images.githubusercontent.com/86565212/207437934-0b084eb1-370b-4bb3-85dc-1c13ae679165.jpeg)
![Machine](https://user-images.githubusercontent.com/86565212/207437938-8c33cac5-bf0d-4317-bf95-34166db516fe.jpeg)
![Team Member](https://user-images.githubusercontent.com/86565212/207437941-30b25181-c872-4d79-9fbc-00dc2ad95c12.jpeg)

* Video

https://user-images.githubusercontent.com/86565212/207436514-4396faf5-312a-45d5-a6ff-b8039a504d34.mp4




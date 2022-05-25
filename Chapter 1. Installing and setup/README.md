# Chapter 1: Installing and setup

We will use STM32CubeIDE to program the STM32 boards. This guide provides information on how to install and setup the IDE and the necessary libraries.

## What is STM32CubeIDE

STM32CubeIDE is an IDE (Integrated Development Environment) for the STM32 microcontrollers. It is a software application that makes it easier to program your STM32 microcontrollers. 

## How to install it?

Go to the software download page at: https://www.st.com/en/development-tools/stm32cubeide.html.

and download the installer for your system.
<p align="center"> 
    <img src = "downloadIDE.png">
</p>

Run the installer and use the default settings.

## Introduction to use the STM32CubeIDE

## Create your first STM32 Project
In the top left corner, click on File → New → STM32 Project  

<p align="center"> 
    <img src = "newProject.png">
</p>

Go to the Board Selector Tab and search for your specific board. Since you probably are going to be using the board for other projects we recommend that you mark the board as a favorite to find it faster next time. 


<p align="center"> 
    <img src = "firstProject.png">
</p>

Name your project and click finish. Wait a few seconds for your IDE to setup the project file.


<p align="center"> 
    <img src = "mcViewioc.png">
</p>



The Basic concept of the IDE is that you have an *.ioc* project file where you see the pinout of the microcontroller. It is in this view you can click on the different pins and specify how they should be configured. Once you have specified the pin configurations in the *.ioc* file, the IDE automatically generates a *main.c* file that initializes the microcontroller based on the configurations specified in the *.ioc* file.







# Clips Flower Expert System Demo

## Introduction
Simple GUI based Expert System that asks you a couple of questions about a certain flower, and answers with its name as a result.<br>

Done for **CSE386: Artificial Intelligence** Course, at Faculty of Engineering, Ain Shams University.

### Technologies Used
- [*Java*](https://www.java.com/en) programming language.
- [*Clips*](http://www.clipsrules.net) Tool for Building Expert Systems

## Installation
- Download [**Java SE Development Kit**](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  - Install JDK and JRE
  - Add `jdk/bin` to your environment path
- Download [**MinGW**](https://sourceforge.net/projects/mingw/)
  - Follow [this](https://www.youtube.com/watch?v=sXW2VLrQ3Bs) tutorial for installation
- Download [**Chocolatey**](https://chocolatey.org/docs/installation)
  - Install `make` package by running the following command:
    >choco install make <br>

## Getting Started
1. Clone this repo.
2. Copy `CLIPSJNI.dll` file to `C:\Windows\System32`.
3. Open a **new** terminal in the repo folder and run the following commands:
    >make -f makefile.linux all <br>
    
    `FlowerDemo.jar` file should be generated in the projects' root directory as a result.
4. Run the `FlowerDemo.jar` file by double clicking on it, or simply by running the following command:
    >java -jar FlowerDemo.jar <br>
    
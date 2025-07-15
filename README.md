# Welcome
Welcome to my GitHub profile.

## About Me
I'm a 21 year old Computer Science student that has recently graduated from the University of Kent, where I achieved a 1st class degree. My interests include: programming language development/implementation, software development, computational creativity and library development.

Below I detail my current projects. Please read the individual READMEs for more information about each project.

## Open source contributions

### [SOM](https://github.com/rhys-h-walker/SOM/) - Testing framework for the SOM language
SOM is an research language based on Smalltalk, it is used primarily for reseach into virtual machine and interpreter development. The integration tests that I developed for the language were supervised at the University of Kent and developed using Pytest.

This specific repository is the core library for SOM and is used in all other implementations of the language.

### [SOMpp](https://github.com/rhys-h-walker/SOMpp) - Raised Vector class to be Primitive
This was also worked on during my time at the univesity and involved writing a primitive class for Vector in c++. This saw improvements in speed to Benchmarks that highly involved the Vector class, such as Knapsack (Roughly 93% improvement).

## Personal projects

### [Callisto](https://github.com/rhys-h-walker/Callisto) - A Modern Collections Library for Java
This project was my final research project at the University of Kent, it is a modern dynamic collections library that aims to bring strategies to a Java based collections framework.

It is made of three main classes: Sequence, Map and Set. Currently only Sequence features strategies, it is a Vector like structure which can maintain a sort specified by a constructor, as well as native support for functioning like a Stack, Queue and by virtue a Priority Stack and Queue.

Please take a look at the paper I wrote for this module which details how Callisto works at the time of submission.

### [Rambling Jesters](https://github.com/rhys-h-walker/rambling-jesters) - A Computational Creativity Experiment
Rambling Jesters is a project that takes a corpus of source text and can generate new text through agent interaction and generative ai refinement. This repository features a GUI (developed with the MVC architecture) for launching new interactions with the Jesters.

The project was part of my University of Kent studies and the branch [command-line-version](https://github.com/rhys-h-walker/rambling-jesters/tree/command-line-version) is the project at the time of submission. Please take a look at the paper I wrote for this module which details how the interactions work at this time.


### [OnRails Logging](https://github.com/rhys-h-walker/OnRailsLogging) -  A simple logging framework for small projects
This is a logging framework that can easily be setup and installed into any project that you start. It features 6 different log types (ERROR, PROGRESS, INFO, WARN, DEBUG, MISC), every time a different log is created it is outputted to a folder in the user.home directory. Documentation exists in the project to explain how to use it, please take a look and give it a go.

### [Environment Sensor](https://github.com/rhys-h-walker/Environment-Sensor) - Humidity, Temperature and Gas sensor with a GUI
A simple Arduino based device which can report temperature, humidity and gas content to a python tkinter GUI through MQTT, and a server which can listen to these inputs and track historic data. It features a simple data analysis tools and historic graph viewing.

This was also part of my degree at the University of Kent, please take a look, the README details how to assemble the device and run the project.
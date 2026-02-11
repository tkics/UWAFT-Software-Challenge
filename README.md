# UWAFT Software Challenge
Welcome to the UWAFT "Hack the Move" 2026 hackathon! This challenge will introduce you to the the controls and programming behind autonomous driving. In this repository you will find all the necessary guides and files to complete the software challenge. You will be using MATLAB and Simulink to write your code and simulate it on a virtual enviornment called QLabs which will show how the car responds to your programming.

## Introduction
In this Hackathon you will be playing the role of an autonmous taxi service. Your goal is to pick up a passenger and drop them off at a specified location. You may choose one of the specified paths shown below to complete the task based on the level of difficulty you are willing to take on. The car must fully function under criteria outlined below to gain the additional points.

<img src="/images/map.png" width="500">

Level 1 (+2 Points): The provided file you will be working off of comes with a predefined path that allows the car to drive around the outer track. To complete level 1, you **do not have to obey traffic signals**. Just stop within a radius of **X** at the coordinates provided for **3 seconds** for this level to be completed.

Level 2 (+8 points): You will have to define a new path for the car shown in blue while also using object detection to obey traffic signals including the stop sign and traffic light.

Level 3 (+16 points): The car wil have t navigate through a more difficult path and also avoid hitting pedestrians at the crosswalk while still stopping for the stop sign and traffic light.

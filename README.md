# Collecting motion data with motion transition implementation

## Introduction

In order to produce motion data, motion
capture system used as a tool to produce motion
data by performing the movement on motion
capture system. The purpose of this research
project is to collect motion data that can be used
in locomotion synthesis with motion transition
and to show the visualization results from the
motion transition to obtain the movement from
current movement to the next movement.
Our method us Motion transitions method to
combine motions sequences to get a new
sequences of motions. In order to collect motion
data of a humanoid character, we first capture
motions of a human subject by acting in a various
ways such as walking, stepping, turning, and
other ways of movements in various orientations
in motion capture system then we process the
motion data in Visual Studio to be used in motion
transition implementation.


## Motion Capture
Motion capture are popular for creating digital
human animation. By using motion capture, user
can control body movements while producing
movement. Markers or sensors are attached to
user and connected to the optical camera.
We used Optitrack system as a motion capture
provider to make a 3D model human interactive
movement. In the process of recording motion, we
measure orientation, ground plane, number of
steps, and type of movement.
![Picture1]

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/22293987/148554310-ac4807eb-908d-4153-a893-a6c81f208c86.png">
  </p>
  <p align="center">
   Fig 1: Motive software interface
  </p>
  We also used Motive software as a optical motion capture software supported by Optitrack system for editing, rendering and exporting motion data files. Motive is a software platform designed to control motion capture systems for various tracking applications.It also provides interfaces for both capturing and processing of 3D data. The captured data can be both recorded or live-streamed to other pipelines.




## Motion Data
Motion data is a digital human animation data results from motion capture that has been processed and exported to be used in research. The following file of motion data used in this research project is .bvh file forrmat. We process motion data to Visual studio software to implement transition by using motion transition method.

<p align="center">
  <img width="300" height="300" src="https://user-images.githubusercontent.com/22293987/148558419-b3e2acd8-3d9b-4f24-97e1-71adce302e60.png">
  </p>
  <p align="center">
   Fig 2: Example of motion data
  </p>
## Motion Transition
Transitions is a standard method which combine motions sequences to create a new sequences while changing into another motion. Transition used as an important role to increase responsiveness of character in interactive applications.

<p align="center">
  <img width="400" height="200" src="https://user-images.githubusercontent.com/22293987/148559938-588a4c71-7f1a-45df-b917-f2d6eb4a0f8a.png">
  </p>
  <p align="center">
   Fig 3: Motion transition example
  </p>
  
## Motion Movement
The following list of motions movements that will be used in the following research are described on the list below
Movement	Total
- Standing pose motion: 1
- Walking motion: 1
- Normal Walk: 1
- Running motion: 1
- Slow motion: 1
- Turning Right: 8
- Turning Left: 8
- Side-step holonomic right: 	4
- Side-step holonomic left: 4
- Side-step nonholonomic right: 	4
- Side-step nonholonomic left: 	4
- Walking back motion: 	1
-	Total: 37

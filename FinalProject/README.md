# Final Project - Robot
**COLLABORATORS**  
Group Member: Gilberto Ruiz, Gloria Hu, Ben Setel, Kenneth Lee, Yifan Yu, Michael Hanlon 

## Project Idea

For our final project, we will build a small robot with the 3D printers here at the Makerspace and its purpose is to mimic a person using the Mediapipe library. The robot will be capable of tracking the user's head, shoulders, elbows and hand movements. 


## Description

The main idea behind our project is to create an “avatar” robot which mimics the movements of the user that is being tracked. We track the user’s movement through the use of a webcam and mediapipe, which digitally maps out the arms and head and provides this data in a form that we can use to control the robot in similar ways. This data about the user’s movement is translated into movements that the robot can make with its arms, which are enabled through its built-in servos and motors.

## Robot Design:

### Source
The stl files to 3D print the robot was found online in the following link: 
[Robot](https://www.kevsrobots.com/blog/chip.html#download-the-3d-printable-stl-files)
 
With the stl files, we were able to print all the pieces to build the robot and these were the results:  

<img width="514" alt="d42f31d152769bb6e08ec8afa3e4684" src="https://github.com/yifanwow/Interactive-Lab-Hub/assets/64716158/1c4c49c0-52f6-465a-b751-67eb9f8cefcb">

We made the decision to not print the legs of the robot and focus more on the head and arm movement due to time constraints and resources with servos.    
  
  


### Servo Motor Wiring:
After building the robot with all its servos, we now needed to wire the servos to the following servo motor driver:  

<img width="306" alt="4d3e5ea447525edca4f25e946e3d7b5" src="https://github.com/yifanwow/Interactive-Lab-Hub/assets/64716158/fa2e7883-995e-4e2b-afb3-d211298f077a">

And with this driver, this is where we assigned each servo motor:  

<img width="760" alt="0001496166b1d40e21a325a81380f4b" src="https://github.com/yifanwow/Interactive-Lab-Hub/assets/64716158/d6e7dca0-2eb6-4e93-8d57-196ef0bc20ff">


| Servo Driver Port | Motor Assignment |
|-----------------|-----------------|
| 0 | Left Hand |
| 1 | Left Elbow |
| 2 | Left Shoulder |
| 3 | Head |
| 12 | Right Shoulder |
| 13 | Right Elbow |
| 14 | Right Hand |

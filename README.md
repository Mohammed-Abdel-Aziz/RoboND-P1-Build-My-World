# RoboND-P1-Build-My-World:
## Project-1 "Build My World" of Udacity Robotics Software Engineer Nanodegree Program. ##

![default_gzclient_camera(1)-2021-06-20T13_55_08 956319](https://user-images.githubusercontent.com/47191401/122677275-f698fc00-d1e1-11eb-85a3-45a5e442758e.jpg)

# Project Aspects:
 * Udacity Office: A building model designed on the Building Editor tool of Gazebo. The structure contains features, and colors.
 * Green humanoid robot: Two instances of a model designed on the Model Editor tool of Gazebo.
 * Tables: A model imported from the Gazebo online library.
 * Terminal: A welcome message generated from a world plugin and printed to the terminal.

## Directory Structure: ##
```
    .Project1                          # Build My World Project 
    ├── model                          # Model files 
    │   ├── Building
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── HumanoidRobot
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script      
    │   ├── welcome_message.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── UdacityOffice.world
    ├── CMakeLists.txt                 # Link libraries 
    └──  
```

## Project Rubric: ##
### Basic Requirements ###
**The student submitted all required files specified in the criteria.**
You have submitted all the required files. Good Job!

### Building ###
**The student designeda structure and stored it in the model directory.**
You have designed an office using the building editor tool. You stored the files under the model directory. Your office world has a single floor,it also has enough space for robots to navigate, and has multiple features and colors. Nice work!

### Modeling ###
**The student designed an object and stored it in the model directory.**
You have designed an object using the model editor tool in Gazebo. You stored your object model files under the model directory of your project. Model links are connected through joints. Awesome Job!

### Gazebo World ###
**The student created a Gazebo world and stored it in the world directory.**
You have designed an office using the building editor tool. You stored the files under the model directory. And you include Gazebo online library.

### World Plugin ###
**The student created a C++ plugin and stored it in the script directory. Also, the student created a CMakeLists.txt file and stored in the main project directory.**
Great! Your plugin work as expected by displaying welcoming message in a terminal in a right format.

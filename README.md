# RoboND-gazebo-poc
A sample project to try out gazebo, the building &amp; model editors, as well as writing a custom plugin

#### Gazebo Introduction
Gazebo is a physics-based, high fidelity 3D simulator for robotics. Gazebo provides the ability to accurately simulate one or more robots in complex indoor and outdoor environments filled with static and dynamic objects, realistic lighting, and programmable interactions.

#### Scope of this POC

The main objective is to use Gazebo to create a simulation of a 4-wheeled differential drive robot in an environment that mimics a floor in a building containing multiple rooms, walls and obstacles. This also explores how a C++ plugin can be used to interact with the world in Gazebo.

The main features of gazebo that will be used are:

 - Building of a floor plan using the Building Editor tool in Gazebo.
 - Apply features such as doors, windows, textures, etc.
 - Use the Model Editor tool to create a model of a 4-wheeled differential drive robot, with links and joints.
 - Explore the Gazebo online library
 - Write a C++ plugin that can interact with the world (right now it just outputs a static message)

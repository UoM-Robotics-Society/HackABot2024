# MONA Background

![MONA](Mona.jpg?raw=true "MONA")


Swarm robotics is a field of research that explores the behaviour of large groups of simple robots that work together to achieve a common goal. The study of swarm robotics is motivated by the desire to develop intelligent, adaptive, and robust systems that can perform complex tasks in dynamic and uncertain environments.

One platform developed to enable researchers in this field were the MONA robots by the University of Manchester and sold by Ice9Robotics. These Arduino based differential drive robots can be used in many applications with a wide range of versatile features.

Many studies have looked at maze solving and complete mapping with use of swarm robots, as centralised control can allow for multiple robots to work together to map a maze in reduced time, making the benefits of swarm robots outweight the additional complexity of the swarm. 

# Challenge

## <div align="center"> Create a basic swarm to navigate and map the whole maze. </div>

## Info

Each team will be issued with 2 MONA robots, an Arduino Uno and 3 NRF24 radio modules to help in the challenge.

3 mazes of a 5x5 grid (each square approx 120mmx 120mm) have been made for you to trial and perfect your swarm algorithms. Each slightly different with additonal complexity which will be in the final challenge maze. 

2 identical final 7x7 grid mazes will be use to assess each teams swarm ability where the judges will look for quickest system to map the maze along which best graphical represenation of the mapped maze.

The starting location of the MONA robots will be known in each case (0,0) and (4,4) for the 5x5 maze and (0,0) and (6,6) for the final maze. orientation of the robots is left to your choice.

The suggested route would involve:
-	Develop the odometry and localisation for controlling the robots
-	Generate a graphical map using something like pygame
-	PC-to-Robot communication
-	Basic centralised swarm algorithm for control

Only 1 teams can test at a time in each maze.

Useful links to information, websites and examples can be found in the [info](info) folder.

For extra points, each team can fill out the MONA robot survey to provide feedback on the robots to help future development.

Winners will get prizes as well as their solution being hosted on the Ice9Robotics GitHub for people to reference in CV, LinkedIn and other mediums.


## Rules/Equipment:
-	Teams can use any resources online or otherwise to help them accomplish the task. 
-	Teams are not allowed to remove the plastic battery cover.
-	Teams are allowed to operate the robots on any table surface, on the ground away from foot traffic, or in the arena.
-	Teams are allowed to modify and add things to the MONA robots to help improve there chances given it doesn’t damage the system (this will likely not be very useful this year).
-	If the system or the battery become damaged in anyway report it to a supervisor (blue shirt) and they will assist.
-	Teams will have access to anything in the inventory which they may use in their solution.
-	Speed is key, you must use 2 robots for the mapping purpose.
-	The MONAs can not be teleoperated, all solutions must be autonomous.



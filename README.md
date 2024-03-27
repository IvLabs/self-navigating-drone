# Frontier-based exploration

## Objective

To carry out autonomous frontier-based exploration of an unknown indoor environment.

Frontiers refers to the points on the boundary between
open space and unexplored space. By moving to new frontiers, a mobile robot can extend its map into unknown territory
until the entire environment has been explored.

![ezgif com-video-to-gif (3)](https://github.com/mayanklonkar/Frontier-based-exploration/assets/108993449/748d3e5f-0d59-495a-817c-bb19bdc58c1f)

## Turtlebot3 Implementations 

Preliminary results are obtained using Explore_lite node of ROS.

#### Nodes used for simulation
1. Move_base
2. Gmapping
3. Explore_Lite

To run this simulation 

- Start Gazebo simulator and spawn Turtlebot 3


` export TURTLEBOT3_MODEL=waffle` 


`roslaunch turtlebot3_gazebo turtlebot3_world.launch`

- Run the following launch files


`export TURTLEBOT3_MODEL=waffle`

`roslaunch turtlebot3_navigation turtlebot3_navigation.launch `

`export TURTLEBOT3_MODEL=waffle`

`
roslaunch turtlebot3_slam turtlebot3_gmapping.launch`

`roslaunch explore_lite explore.launch`









# Launch Instructions

## Step 1: Launch House World

 ros2 launch turtlebot3_gazebo turtlebot3_house.launch.py

## Step 2: Launch Nav2

 ros2 launch turtlebot3_navigation2 navigation2.launch.py use_sim_time:=True

## Step 3: In RViz

 Click 2D Pose Estimate → set robot starting pose

 Click Nav2 Goal → set navigation goal
 
 🎉 Robot navigates autonomously!

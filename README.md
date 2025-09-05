# Autonomous Navigator in ROS 2 (TurtleBot3 + Gazebo)

🚀 This project demonstrates a simple autonomous navigation system using **ROS 2 Humble**, **Nav2**, and **Gazebo**.  
The robot localizes itself and autonomously navigates to a target location while avoiding obstacles.  

## How to Run
```bash
# Terminal 1 - Launch house world
ros2 launch turtlebot3_gazebo turtlebot3_house.launch.py

# Terminal 2 - Launch Nav2
ros2 launch turtlebot3_navigation2 navigation2.launch.py use_sim_time:=True

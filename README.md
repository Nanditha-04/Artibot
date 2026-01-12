					             SLAM_BOT
					             
					             
COMMANDS:				             
					         
TO LAUNCH WORLD IN GAZEBO:
					   
 1.ros2 launch artibot launch_sim.launch.py world:=/home/Username/dev_ws/src/artibot/worlds/obstacles.world
 
TO MAP THE WORLD:

2.ros2 launch slam_toolbox online_async_launch.py params_file:=./src/artibot/config/mapper_params_online_async.yaml use_sim_time:=true 

TO RUN THE BOT 

3.ros2 run teleop_twist_keyboard teleop_twist_keyboard

VISUALIZATIO

4.rviz2

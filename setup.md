 Для начала работы с `move_it` необходимо установить следующие пакеты
 
`sudo apt install ros-kinetic-moveit`

`git clone https://github.com/ros-planning/moveit_tutorials.git -b master`

`git clone https://github.com/ros-planning/panda_moveit_config.git -b noetic-devel`

`git clone https://github.com/frankaemika/franka_ros.git`

`cp -a franka_ros/franka_description/ . && rm -rf franka_ros`

`git clone https://github.com/ros-planning/moveit_visual_tools.git`

[ERROR] [1680208932.319630848]: PluginlibFactory: The plugin for class 'rviz_visual_tools/KeyTool' failed to load.  Error: According to the loaded plugin descriptions the class rviz_visual_tools/KeyTool with base class type rviz::Tool does not exist. Declared types are  rviz/FocusCamera rviz/Interact rviz/Measure rviz/MoveCamera rviz/PublishPoint rviz/Select rviz/SetGoal rviz/SetInitialPose rviz_plugin_tutorials/PlantFlag

`sudo apt-get install ros-noetic-moveit-ros-visualization
`
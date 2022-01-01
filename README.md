# ROS1
## turtlebot3 auto driving along walls and parking at Green color  

turtlebot3, DynamixelSDK, turtlebot3_msgs, turtlebot3_simulation 설치는 https://github.com/ROBOTIS-GIT 참고하세요 

project.world 를 turtlebot3_gazebo/worlds 에 추가하세요

turtlebot3_burger에 카메라를 추가하기 위하여 turtlebot3_burger.urdf.xacro 를 교체

turtlebot3_project.launch 를 turtlebot3_gazebo/launch 에 추가

$catkin build
$source setup.bash
$roslaunch turtlebot3_gazebo tuturtlebot3_project.launch 
project.py 구동 프로그램 실행

자세한 설명과 실행결과는 아래 참조
https://www.notion.so/Wall-Wall-6895127764ed42f1b28e1ca94b2f4086

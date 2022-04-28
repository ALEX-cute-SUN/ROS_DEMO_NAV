# ROS_DEMO_NAV
ros-based navigation items


lab environment:ubuntu 18.04 + ros_melodic

GETTING STARTED:
  
 下载： 
 
    git clone https://github.com/ALEX-cute-SUN/ROS_DEMO_NAV.git
    
 解压：
 
  7z x demo05_nav.7z -r -o./
  
 进入目录：
 
  cd demo05_nav
  
 开启终端1：
 
    添加环境变量：
      source ./devel/setup.bash
      
    启动gazebo：
      roslaunch urdf02_gazebo demo03_env.launch
    
 开启终端2：
 
    添加环境变量：
      source ./devel/setup.bash
      
    启动rviz：
      roslaunch nav_demo nav07_test.launch 
 

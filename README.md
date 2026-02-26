# split aloha 

## 使用环境

Ubuntu 22.04；ROS2 humble

## 使用方法

创建工作空间

```
mkdir -p agilex_ws/src
cd agilex_ws/src
```

下载代码并编译

```
cd agilex_ws/src
git clone https://github.com/agilexrobotics/mobile_aloha_sim_ros2.git -b split_aloha
cd agilex_ws/
colcon build 
```

查看模型

```
cd agilex_ws/
source install/setup.bash
ros2 launch split_aloha_mid_360 display_xacro.launch.py
```

![](./img/split_aloha_mid_360.png)














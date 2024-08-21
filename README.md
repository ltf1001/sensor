**按照Ego-Planner 安装对应的配置环境**
仅需修改话题：1、相机深度图像话题：/camera/depth/image_raw
            2、同时修改里程计的话题：/odom
*注*：如果无法实现注意世界坐标系的修改（此代码中的世界坐标系是：odom.可修改为自己的世界坐标系，例如：map.world等）
完成后进行:
1、catkin_make
2、roslaunch plan_env grid_map.launch

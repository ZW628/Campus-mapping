# 介绍
使用LIDAR+IMU+CAMERA等多传感器SLAM算法对浙江科技学院校园建图
# 实验平台
![image](https://github.com/ZW628/Campus-mapping/blob/main/1.png)

# 教学楼校园环境
道路条件：柏油路、水泥路、碎石路（车辆较颠簸）

树木和教学楼较多；
![image](https://github.com/ZW628/Campus-mapping/blob/main/2.png)

## 建图效果对比
### LeGO-LOAM
![image](https://github.com/ZW628/Campus-mapping/blob/main/5.png)

### LIO-SAM
![image](https://github.com/ZW628/Campus-mapping/blob/main/4.png)

### LVI-SAM
![image](https://github.com/ZW628/Campus-mapping/blob/main/3.png)

## EVO轨迹误差评价
![image](https://github.com/ZW628/Campus-mapping/blob/main/6.png)

# 长坡道路环境
长上坡+长下坡、树木较多

![image](https://github.com/ZW628/Campus-mapping/blob/main/7.png)

## 建图效果对比
整体建图效果、回环检测效果对比

回环处Z轴误差：LIO-SAM>LeGO-LOAM>LVI-SAM

![image](https://github.com/ZW628/Campus-mapping/blob/main/8.png)

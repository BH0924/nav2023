# 23赛季定位导航

nav_2023中有3个版本的代码：

|     代码名称      |                    说明                    |
| :---------------: | :----------------------------------------: |
|  exploration_530  |  分区赛上场代码，导航随动，未添加全局规划  |
| exploration_3_ws  |     导航随动代码和全向移动代码过渡版本     |
| exploration726_ws | 全国赛上场代码，导航全向移动，增加全局规划 |
| exploration11_ws | 增加动态代价地图 |

## 环境配置

代码基于ubuntu20.04+ros-noetic开发，需要配置以下驱动及安装包。

1. Livox-SDK

   ```
   https://github.com/Livox-SDK
   ```

2. livox-ros-driver2

   ```
   https://github.com/Livox-SDK
   ```

3. realsense-ros

   ```
   https://github.com/IntelRealSense/realsense-ros
   ```

4. LIO-Livox , Fast-LIO , Faster-LIO 和 Point-LIO

   ```
   https://github.com/Livox-SDK/LIO-Livox
   https://github.com/hku-mars/FAST_LIO
   https://github.com/gaoxiang12/faster-lio
   https://github.com/hku-mars/Point-LIO
   ```

5. cmu-exploration仿真环境安装

   ```
   https://www.cmu-exploration.com
   https://github.com/HongbiaoZ/autonomous_exploration_development_environment
   ```

   




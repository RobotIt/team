# 1 重点论文

## 1 移动机器人运动控制

### 1.1  室外建图及导航

Project page: 

https://www.ri.cmu.edu/enabling-autonomous-exploration/

https://www.cmu-exploration.com/

PDF:

FAR Planner: [点击下载](./files/FAR Planner Fast, Attemptable Route Planner using Dynamic Visibility Update.pdf)

TARE: [点击下载](./files/TARE A Hierarchical Framework for Efficiently Exploring Complex 3D Environments.pdf)

Autonomous exploration: [点击下载](./files/Representation granularity enables time-efficient autonomous exploration in large, complex worlds.pdf)



## 2 机械臂视觉抓取

### 2.1  强化学习+机械臂

#### 1 robopal

Github: https://github.com/NoneJou072/robopal

**robopal** 是一个基于 [MuJoCo](http://mujoco.org/) 动力学引擎与 [pinocchio](https://gepettoweb.laas.fr/doc/stack-of-tasks/pinocchio/master/doxygen-html/index.html) 机器人动力学库搭建的多平台开源机器人仿真框架，主要用于机械臂的深度强化学习训练与控制算法验证



#### 2   [drl_grasping](https://github.com/AndrejOrsula/drl_grasping) ⭐ 2022 IROS

通过深度强化学习来获得一种稳健的策略，使机器人能够从八叉树形式的紧凑三维观测中抓取各种物体

Github: https://github.com/andrejorsula/drl_grasping

PDF: [点击下载](./files/Learning to Grasp on the Moon from 3D Octree Observations with Deep Reinforcement Learning.pdf)



#### 3 [Collaborative-Pushing-Grasping](https://github.com/nizhihao/Collaborative-Pushing-Grasping) 2022

堆叠物品的分离抓取，用Yolov8进行平面抓取，使用Ubuntu16.04

Github: https://github.com/nizhihao/Collaborative-Pushing-Grasping

PDF: [点击下载](./files/Collaborative Pushing and Grasping of Tightly Stacked Objects via Deep Reinforcement Learning.pdf)



#### 4 [Eureka](https://github.com/eureka-research/Eureka) 2023 

通过编写大型语言模型进行人性化的奖励设计，Github很多star，LLM+RL

Github: https://github.com/eureka-research/Eureka

PDF: [点击下载](./files/Eureka Human-Level Reward Design via Coding Large Language Models.pdf)





### 2.2 大语言模型+机械臂

#### 1 VoxPoser 2023 ArXiv

零样本操控机器人，李飞飞团队新作Voxposer

Project page: https://voxposer.github.io/   (代码暂未开源)

PDF: [点击下载](./files/VoxPoser Composable 3D Value Maps for Robotic Manipulation with Language Models for Robotic Manipulation with Language Models.pdf)



#### 2 Language to Rewards for Robotic Skill Synthesis 2023 CoRL

利用大型语言模型 (LLM) 和奖励函数来优化机器人控制的方法

Project page: https://language-to-reward.github.io/   (代码暂未开源)

PDF: [点击下载](./files/Language to Rewards for Robotic Skill Synthesis.pdf)



#### 3 RobotCat 2023 ArXiv

谷歌DeepMind推出了一种可以自我改进、自我提升（self-improving）的用于机器人的AI智能体

Github: https://github.com/kyegomez/RoboCAT

PDF: [点击下载](./files/RoboCat A Self-Improving Foundation Agent for Robotic Manipulation.pdf)



#### 4 RoboAgent  2023 ArXiv

一种AI智能体，利用被动观察和主动学习，使机器人能够获得与幼儿同等的操作能力

Project page: https://robopen.github.io/

PDF:  [点击下载](./files/RoboAgent Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking.pdf)





### 2.3 其他视觉抓取

#### 1 GraspNeRF  2023 ICRA

使用通用 NeRF 对透明和镜面物体进行基于多视图的 6-DoF 抓取检测

Project page: https://pku-epic.github.io/GraspNeRF/

PDF: [点击下载](./files/GraspNeRF Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF.pdf)



#### 2 Transporter Networks  2020 CoRL

基于视觉操作实现重新整理目标物体

Project page: https://transporternets.github.io/

PDF: [点击下载](./files/Transporter Networks Rearranging the Visual World for Robotic Manipulation.pdf)



#### 3 CLIPort  2021 CoRL 

一个端到端模仿学习agent，可以为各种桌面任务学习单一语言条件策略

Project page: https://cliport.github.io/

PDF: [点击下载](./files/CLIPORT What and Where Pathways for Robotic Manipulation .pdf)



#### 4 CaTGrasp  2022  ICRA⭐

任务驱动的类级别机器人抓取

Github: https://github.com/wenbowen123/catgrasp

PDF: [点击下载](./files/CaTGrasp_Learning_Category-Level_Task-Relevant_Grasping_in_Clutter_from_Simulation.pdf)



### 2.4 平面抓取

#### 1 Yolov8_ros

GIthub: https://github.com/qq44642754a/Yolov8_ros





## 3 ROS+大语言模型

#### 3.1 Langchain-Robotic

基于 ROS2 与 langchain 的仿真框架示例（暂未包含机器人仿真环境，需要自行搭建），用于使用大语言模型对机器人进行决策与规划

Github: https://github.com/NoneJou072/robochain








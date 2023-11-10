# 1 重点论文

网盘链接：https://pan.baidu.com/s/1eV-y5bpQIysiurXBD6dylA 



## 1 机械臂视觉抓取

### 1.1  强化学习+机械臂

#### 1 robopal

Github: https://github.com/NoneJou072/robopal

**robopal** 是一个基于 [MuJoCo](http://mujoco.org/) 动力学引擎与 [pinocchio](https://gepettoweb.laas.fr/doc/stack-of-tasks/pinocchio/master/doxygen-html/index.html) 机器人动力学库搭建的多平台开源机器人仿真框架，主要用于机械臂的深度强化学习训练与控制算法验证



#### 2 [drl_grasping](https://github.com/AndrejOrsula/drl_grasping) ⭐ 2022 IROS

通过深度强化学习来获得一种稳健的策略，使机器人能够从八叉树形式的紧凑三维观测中抓取各种物体

Github: https://github.com/andrejorsula/drl_grasping

论文: Learning to Grasp on the Moon from 3D Octree Observations with Deep Reinforcement Learning



#### 3 [Collaborative-Pushing-Grasping](https://github.com/nizhihao/Collaborative-Pushing-Grasping) 2022

堆叠物品的分离抓取，用Yolov8进行平面抓取，使用Ubuntu16.04

Github: https://github.com/nizhihao/Collaborative-Pushing-Grasping

论文: Collaborative Pushing and Grasping of Tightly Stacked Objects via Deep Reinforcement Learning



#### 4 [Eureka](https://github.com/eureka-research/Eureka) 2023 

通过编写大型语言模型进行人性化的奖励设计，Github很多star，LLM+RL

Github: https://github.com/eureka-research/Eureka

论文: Eureka Human-Level Reward Design via Coding Large Language Models



### 1.2 大语言模型+机械臂

#### 1 VoxPoser 2023 ArXiv

零样本操控机器人，李飞飞团队新作Voxposer

Project page: https://voxposer.github.io/   (代码暂未开源)

论文: VoxPoser Composable 3D Value Maps for Robotic Manipulation with Language Models for Robotic Manipulation with Language Models



#### 2 Language to Rewards for Robotic Skill Synthesis 2023 CoRL

利用大型语言模型 (LLM) 和奖励函数来优化机器人控制的方法

Project page: https://language-to-reward.github.io/   (代码暂未开源)

论文: Language to Rewards for Robotic Skill Synthesis



#### 3 RobotCat 2023 ArXiv

谷歌DeepMind推出了一种可以自我改进、自我提升（self-improving）的用于机器人的AI智能体

Github: https://github.com/kyegomez/RoboCAT

论文: RoboCat A Self-Improving Foundation Agent for Robotic Manipulation



#### 4 RoboAgent  2023 ArXiv

一种AI智能体，利用被动观察和主动学习，使机器人能够获得与幼儿同等的操作能力

Project page: https://robopen.github.io/

论文: RoboAgent Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking



### 1.3 其他视觉抓取

#### 1 GraspNeRF  2023 ICRA

使用通用 NeRF 对透明和镜面物体进行基于多视图的 6-DoF 抓取检测

Project page: https://pku-epic.github.io/GraspNeRF/

论文: GraspNeRF Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF



#### 2 Transporter Networks  2020 CoRL

基于视觉操作实现重新整理目标物体

Project page: https://transporternets.github.io/

论文: Transporter Networks Rearranging the Visual World for Robotic Manipulatio



#### 3 CLIPort  2021 CoRL 

一个端到端模仿学习agent，可以为各种桌面任务学习单一语言条件策略

Project page: https://cliport.github.io/

论文: CLIPORT What and Where Pathways for Robotic Manipulation 



#### 4 CaTGrasp  2022  ICRA⭐

任务驱动的类级别机器人抓取

Github: https://github.com/wenbowen123/catgrasp

论文: CaTGrasp_Learning_Category-Level_Task-Relevant_Grasping_in_Clutter_from_Simulation



### 1.4 平面抓取

#### 1 Yolov8_ros

GIthub: https://github.com/qq44642754a/Yolov8_ros












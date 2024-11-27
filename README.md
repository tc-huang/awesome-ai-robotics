# awesome-ai-robotics
## Library
- [**LeRobot**](https://github.com/huggingface/lerobot) - LeRobot aims to provide models, datasets, and tools for real-world robotics in PyTorch. LeRobot contains state-of-the-art approaches that have been shown to transfer to the real-world with a focus on imitation learning and reinforcement learning.
- [**Universal Manipulation Interface**](https://github.com/real-stanford/universal_manipulation_interface) - In-The-Wild Robot Teaching Without In-The-Wild Robots.
- [**Open-Teach**](https://github.com/aadhithya14/Open-Teach) - A Versatile Teleoperation framework for Robotic Manipulation using Meta Quest3.

## Robotic Arms
### Hardware
#### Low-cost
- [**Low-Cost Robot Arm**](https://github.com/AlexanderKoch-Koch/low_cost_robot) - This repository contains the files to build and control a low-cost robot arm that costs about $250. Such a robot arm is well-suited for robot learning. Two of those arms are also capable of folding clothes.
- [**Low-Cost Robot Arm: Koch v1.1**](https://github.com/jess-moss/koch-v1-1) - A version 1.1 of the Alexander Koch low-cost robot arm with some small changes.
- [**moss-robot-arms**](https://github.com/jess-moss/moss-robot-arms) - A repository for affordable, easy-to-assemble robot arms designed for teleoperation applications.
- [**SO-ARM100**](https://github.com/TheRobotStudio/SO-ARM100) - Standard Open Arm 100.
#### More-cost
- [**Dummy-Robot**](https://github.com/peng-zhihui/Dummy-Robot) - Super compact smart robotic-arm.
[![Star History Chart](https://api.star-history.com/svg?repos=AlexanderKoch-Koch/low_cost_robot,jess-moss/koch-v1-1,jess-moss/moss-robot-arms,TheRobotStudio/SO-ARM100,peng-zhihui/Dummy-Robot&type=Timeline)](https://star-history.com/#AlexanderKoch-Koch/low_cost_robot&jess-moss/koch-v1-1&jess-moss/moss-robot-arms&TheRobotStudio/SO-ARM100&peng-zhihui/Dummy-Robot&Timeline)

### Applications and Demos
#### Real
- [**SimpleAutomation**](https://github.com/1g0rrr/SimpleAutomation) - Opensource robot to automate repetitive tasks. Currently, it's a set of helper scripts on top of LeRobot repo.
[![Star History Chart](https://api.star-history.com/svg?repos=1g0rrr/simpleautomation&type=Timeline)](https://star-history.com/#1g0rrr/simpleautomation&Timeline)
#### Simulation
- [**BiGym**](https://github.com/chernyadev/bigym) - BiGym is a new benchmark and learning environment for mobile bi-manual demo-driven robotic manipulation. BiGym features 40 diverse tasks set in home environments, ranging from simple target reaching to complex kitchen cleaning.
- [**Aloha Bigym Modifications**](https://github.com/AlmondGod/aloha-bigym) - This Fork of Bigym contains the bigym tasks modified to work with the ALOHA bimanual system.

## Mobile Robot
- [**RoBart**](https://github.com/trzy/RoBart) - An iPhone-based LLM-controlled autonomous robot. RoBart began as an attempt to build a cheap mobile base using a hoverboard and iPhone Pro. Mobile phones are easy to work with and provide plenty of compute, connectivity, and useful peripherals: RGB cameras, LiDAR, microphones, speakers.
- [**stretch (hello-robot)**](https://github.com/hello-robot)
- [**ReallyUsefulRobot**](https://github.com/XRobots/ReallyUsefulRobot)
- [**Maxwell**](https://github.com/mikeferguson/maxwell) - Maxwell is a custom mobile manipulator based on the Etherbotix.

## Humanoid
### Robot
- **AgiBot X1**
  - [**agibot_x1_hardware**](https://github.com/AgibotTech/agibot_x1_hardware) - The hardware design for AgiBot X1.
  - [**agibot_x1_infer**](https://github.com/AgibotTech/agibot_x1_infer) - The inference module for AgiBot X1.
  - [**agibot_x1_train**](https://github.com/AgibotTech/agibot_x1_train) - The reinforcement learning training code for AgiBot X1.
- [**rx1 (Red Rabbit Robotics)**](https://github.com/Red-Rabbit-Robotics)
### Teleoperation
- [**Open TeleVision**](https://github.com/OpenTeleVision/TeleVision) - This code contains implementation for teleoperation and imitation learning of Open-TeleVision.

## Frameworks
- [**ROS2**](https://github.com/ros2/ros2) - The Robot Operating System (ROS) is a set of software libraries and tools that help you build robot applications.
- [**dora-rs**](https://github.com/dora-rs/dora) - DORA (Dataflow-Oriented Robotic Architecture) is middleware designed to streamline and simplify the creation of AI-based robotic applications.
  - [**dora-lerobot**](https://github.com/dora-rs/dora-lerobot) - Dora-LeRobot is a 100% Dora pipeline for manipulating robots, cameras and all possible hardware compatible with LeRobot.
- [**AimRT**](https://github.com/AimRT/AimRT) - AimRT is a basic runtime framework for the field of modern robotics. It is developed based on modern C++, is lightweight and easy to deploy, and has more modern designs in resource management and control, asynchronous programming, deployment configuration, etc.
[![Star History Chart](https://api.star-history.com/svg?repos=ros2/ros2,dora-rs/dora,AimRT/AimRT&type=Timeline)](https://star-history.com/#ros2/ros2&dora-rs/dora&AimRT/AimRT&Timeline)

## Simulation
- [**ManiSkill**](https://github.com/haosulab/ManiSkill) - SAPIEN Manipulation Skill Framework, a GPU parallelized robotics simulator and benchmark.

## Visualization
- [**rerun**](https://github.com/rerun-io/rerun) - Visualize streams of multimodal data. Free, fast, easy to use, and simple to integrate. Built in Rust.

## Data Infrastructure
- [**CORTEX**](https://github.com/nasa-jpl/cortex) - CORTEX is a framework for accelerating robotics development through a combination of modern data infrastructure, test automation, and intelligent data analysis. The framework enables developers to rapidly prototype and test new algorithms and ideas with minimal effort.

## ROS2
### ROS2 Packages
- [**rosa**](https://github.com/nasa-jpl/rosa) - ROSA is an AI Agent designed to interact with ROS1- and ROS2-based robotics systems using natural language queries. ROSA helps robot developers inspect, diagnose, understand, and operate robots.
- [**ROS-LLM**](https://github.com/Auromix/ROS-LLM) - ROS-LLM is a framework designed for embodied intelligence applications in ROS. It allows natural language interactions and leverages Large Language Models (LLMs) for decision-making and robot control.
- [**ros2ai**](https://github.com/fujitatomoya/ros2ai) - ros2ai is a next-generation ROS 2 command line interface extension with LLMs.
- [**ros_deep_learning**](https://github.com/dusty-nv/ros_deep_learning) - Deep learning inference nodes for ROS / ROS2 with support for NVIDIA Jetson and TensorRT.
### Dev Tools
- [**VSCode ROS2 Workspace Template**](https://github.com/athackst/vscode_ros2_workspace) - This template will get you set up using ROS2 with VSCode as your IDE.
- [**tracetools_analysis**](https://github.com/ros-tracing/tracetools_analysis) - Utilities for analyzing trace data from ROS 2 systems generated by the ros2_tracing packages.
- [**rviz2-panel**](https://github.com/BruceChanJianLe/rviz2-panel) - This repository demonstrates the method for writing a rviz2 dock-able panel.
- [**fusion2urdf-ros2**](https://github.com/dheena2k2/fusion2urdf-ros2) - A Fusion 360 Script to export URDF for ROS2.

## Learning Source
- [**Modern Robotics**](https://github.com/NxRLab/ModernRobotics) - This repository contains the code library accompanying Modern Robotics: Mechanics, Planning, and Control (Kevin Lynch and Frank Park, Cambridge University Press 2017).
- [**mjctrl**](https://github.com/kevinzakka/mjctrl) - Minimal, clean, single-file implementations of common robotics controllers in MuJoCo.
- [**Pinocchio**](https://github.com/stack-of-tasks/pinocchio) - Pinocchio instantiates the state-of-the-art Rigid Body Algorithms for poly-articulated systems based on revisited Roy Featherstone's algorithms. Besides, Pinocchio provides the analytical derivatives of the main Rigid-Body Algorithms, such as the Recursive Newton-Euler Algorithm or the Articulated-Body Algorithm.
  - [**PyRoboPlan**](https://github.com/sea-bass/pyroboplan) - Educational Python library for manipulator motion planning.This library extensively uses the Pinocchio Python bindings for modeling robot kinematics and dynamics.

## Star History of This List
[![Star History Chart](https://api.star-history.com/svg?repos=tc-huang/awesome-ai-robotics&type=Timeline)](https://star-history.com/#tc-huang/awesome-ai-robotics&Timeline)

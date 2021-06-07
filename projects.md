---
layout: page
title: Projects
permalink: /projects/
---

## Open Source Projects:
- ### [ACM GPU Cluster](https://github.com/acm-uiuc/gpu-cluster)
	Built the docker container management system for the GPU cluster that allows users to have GPU access from a jupyter notebook running in a docker container. This project uses the [nvdocker](https://github.com/acm-uiuc/nvdocker) python library we made to create and run docker containers with GPU access. Essentially we built Google CoLab before Google did.

- ### [nvdocker](https://github.com/acm-uiuc/nvdocker/)
	nvdocker is library built on top of the docker-py python sdk to build and run docker containers with GPU access using nvidia-docker. I am currently one of the maintainers.

- ### [gonum](https://github.com/gonum/gonum/pull/525)
	First contribution to a large open source project. Wrote the Yen K-Shortest Path algorithm for their graph implementation in golang.
	
- ### [plant](https://github.com/arbor-dev/plant)
	A CLI tool to create new arbor projects. [Arbor](https://github.com/arbor-dev/arbor) is a microservices framework built by ACM@UIUC in golang.
	
- ### [cfg](https://github.com/Confbase/cfg)
	A CLI tool to manage configuration files and use them in production. [Confbase](http://www.confbase.com/) is a web service that allows teams to manage their configuration files.
	
## Robotics Projects:
- ### [MotionProfileLib](https://github.com/Team5677Robotics/MotionProfileLib)
	A Java Library that computes 2D trajectories and motor profiles for a skid-steer FRC Robot during the [2017 FRC Game, Steamworks](https://en.wikipedia.org/wiki/FIRST_Steamworks). The generated trajectory is passed through a control loop running at 100Hz using the [WPILib Notifier Library](http://first.wpi.edu/FRC/roborio/release/docs/java/).
	
- ### [FRC Target Tracking](https://github.com/therishidesai/FRC_VisionTracking_2016)
	An OpenCV blob tracker written in Python for [2016 FRC game, Stronghold](https://en.wikipedia.org/wiki/FIRST_Stronghold). This script tracks finds the center of the goal and then calculates the robots offset angle and streams the data to the robots controller via a UDP socket.

- ### [Jetson T-Shirt Shooting Robot](https://github.com/therishidesai/NVIDIABot)
	Converted a FIRST FRC robot into a robot fully run by the NVIDIA Jetson TK1 with ROS and Python. Project was sponsored by NVIDIA. [Here is a video of the robot in action!](https://www.youtube.com/watch?v=AkMDzctFkO0)

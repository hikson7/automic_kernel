---
layout: "post"
title: "Webots: Making a microcontroller"
date: 2021-12-15
categories: webots
---

## TLDR;

# Why Webots?

I like Webots for serveral reasons - it is open source and cross-platform, (can work on MacOS, Linux, Windows etc. for free!) it's features are self-contained (no need to have Gazebo, Rvitz and ROS all running to simulate), and it provides minimal base components that you can tweak to simulate your robot.

I first used this for a course work, using an E-puck robot to implement features for a micro-mouse competition. I'd say there is a slight learning curve, and at the time documentation wasn't exactly helpful at times, but I saw some promise for its use. I liked it much more than OpenGL based graphic simulation, or MATLAB which I simply felt was really unpractical if you're trying to build a robot from scratch. For my first hexapod,  I actually used Webots to help me visualise and validate my inverse kinematics for the legs and the overall tripod gait.

I guess 


# Setup

Ok first we'll create the bodies for testing. You can follow this section or you can find the complete world in the repo.

For simplicity, I used E-puck robot which acts as your "host" computer. We will be adding a separate "robot" object to act as our new microcontroller.


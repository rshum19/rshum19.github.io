---
layout: post
title:  "Momentum based Whole-Body Optimal Planning for a Single- Spherical-Wheeled Balancing Mobile Manipulator"
date:   2019-10-15 22:21:59 +00:00
image: images/GIF/humanoids2019.gif
categories: research
author: "Roberto Shu"
authors: "<strong>Roberto Shu</strong>, Ralph Hollis"
venue: "2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)"
video: "https://www.youtube.com/watch?v=HC_Qk1x228Y"
arxiv: 
slides: 
code: 
poster: 
pdf: papers/rshu_IROS2021_wboc-camera_ready.pdf
---

In this paper, we present a planning and control framework for dynamic, whole-body motions for dynamically stable shape-accelerating mobile manipulators. This class of robots are inherently unstable and require careful coordination between the upper and lower body to maintain balance while performing arm motion tasks. Solutions to this problem either use a complex, full-body nonlinear dynamic model of the robot or a highly simplified model of the robot. Here we explore the use of centroidal dynamics which has recently become a popular approach for designing balancing controllers for humanoid robots. We describe a framework where we first solve a trajectory optimization problem offline. We demonstrate that this framework is capable of generating dynamic motion plans and control inputs with examples on the CMU ballbot, a single-spherical-wheeled balancing mobile manipulator. 

We define balancing for a ballbot in terms of the centroidal momentum instead of other approaches like ZMP or angular velocity that are more commonly used. The generated motion is tracked using a PD-PID cascading balancing controller for the body and torque controller for the arms. 

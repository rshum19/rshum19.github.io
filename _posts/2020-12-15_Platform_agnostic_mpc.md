---
layout: post
title:  "Platform-Agnostic Model Predictive Control"
date:   2020-12-15 22:21:59 +00:00
image: images/Agnostic_mpc/ballbot3d_anim_circle.jpg
categories: other
author: "Roberto Shu"
authors: "<strong>Roberto Shu</strong>, Nikolai Flowers, Ardalan Tajbakhsh, Mike Turski, Roshan Pradhan"
venue: "Carnegie Mellon University"
video: 
arxiv:
pdf: /papers/ACSI_Final_Report.pdf
slides: 
code: "https://github.com/rshum19/LinearMPC/commits/devel/ballbot_sim"
---

In this paper, we present the design and analysis of a platform-agnostic model predictive control (MPC) framework. The MPC is based on formulating a quadratic program (QP) that tracks the error between the desired reference trajectory and the actual robot state. The controller is based on a linear model of the controlled plant. We present linear_mpc an open-source library with MATLAB and C++ bindings that implement the QP based MPC proposed in this work. We show on three different platforms (Tumbller, Subterrenean drone, and Ballbot) in simulation and hardware the usage of the library.
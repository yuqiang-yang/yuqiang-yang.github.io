---
layout: archive
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Yuqiang Yang, a master candidate at [South China University of Technology](https://www.scut.edu.cn/new/), supervised by [Prof. Chenguang Yang](https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao). Now I am also working as an intern at Application Innovate Laboratory, [Huawei Technologies Co.Ltd](www.huawei.com).

My research interests are robotic **wholebody planning and control** for different platforms such as **mobile manipulator, multicopter and car**. Specifically, I have been exploring and exploiting the potentiality of the wheeled mobile manipulators to avoiding collision aggressively in a wholebody manner and finishing pick-and-place task in 3d cluttered dynamic environment. Besides, I am working towards the low-cost and efficient mapping, planning and control framework for **multicopter** in unstructed environment. I have sufficient engineering experience on deploying algorithms in various robotic scenarios such as agile collision avoidance, pedestrian following and picking-placing. The goal of my research is to endow robots with **agile mobility and manoeuvrability** in a 3d cluttered **dynamic** environment.

## Education
**South China University of Technology**
<div style="float:left; text-align:left"><i>Master, Robotics</i></div> <div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br />
<div style="float:left; text-align:left">School of Automation Science and Engineering</div>
<p><br />Supervisor: Prof. Chenguang Yang</p>

**South China University of Technology**
<div style="float:left; text-align:left"><i>Bachelor, School of Automation Science and Engineering</i></div> 
<div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div><br/>
<p>GPA: 3.94/4.0 (ranked first)</p>

## working
**Huawei Technologies Co.Ltd**
<div style="float:left; text-align:left"><i>Intern, Application Innovation Laboratorys</i></div> 
<div style="float:right; text-align:right"><i>June. 2022 - now</i></div><br/>
<p>Planning and Control for various robots</p>

## Research Experiences


**Realtime wholebody control of the mobile manipulator in cluttered environment**
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei</div> <div style="float:right; text-align:right"><i>2022.10 - present</i></div>  
<br />
Advisor: Dr. Chen Chen
<ul>
<li>
   Construct the occupancy grid map and ESDF based on <a href="https://github.com/HKUST-Aerial-Robotics/FIESTA" title="FIESTA">FIESTA</a>. Then bias the sample of RRT* to get an initial guiding path according to the topological map in Cartesian space. 
</li>
<li>
  <p> Propose and analyse the adaptive MPC theoretically to improve the convergence and optimality in complex environments where multiple non-convex costs or constraints exist</p>
</li>
<li>
  <p>The proposed framework is verified through experiments about picking and placing a cup gracefully in cluttered environments.</p>
</li>
</ul>

**Learning the coordination motion of mobile  manipulators through human demonstration**
<div style="float:left; text-align:left">School of Automation Science and Engineering, SCUT</div> <div style="float:right; text-align:right"><i>2022.01 - 2022.09</i></div>
<p> <br />
Advisor: Prof. Chenguang Yang</p>
<ul>
<li>
  <p>Propose a
whole-body LfD framework through Gaussian Process, which
endows the mobile manipulator’s skill learning process with
features of large-scale convergence, coordination working and
disturbance rejection, after just a few human demonstrations.</p>
</li>
<li>
  <p>An
efficient kinesthetic teaching method is devised based on the
weighted least-norm (WLN) inverse kinematics solution and an
admittance controller, which facilitates human users to guide
the mobile manipulator to perform tasks.</p>
</li>
<li>
  <p> The framework allows for human-in-the-loop correction when the whole-body is conducting a task.</p>
</li>
</ul>

## Project Experiences
**Self-balanced smart car with wireless charging capability**
<div style="float:left; text-align:left">School of Automation Science and Engineering, SCUT</div> <div style="float:right; text-align:right"><i>2020.01 - 2020.08</i></div>
<p> <br />
Advisor: Dr. An Chen</p>
<ul>
<li>
  <p>Design and implement the adaptive wireless-charging algorithm to quickly charge the supercapacitors mounted on the car. A series control system from the charging power loop to the charging current loop is designed to stabilize the charging power at 30W.</p>
</li>
<li>
  <p> Control the position and orientation of the two-wheeled car to complete a complex race track with different elements such as circles and slopes. The perception information mainly comes from the onboard IMU and electromagnetic sensors.</p>
</li>
<li>
  <p> We finished the race in fifth national ranking with a time of 23.8s and won the first prize.</p>
</li>
</ul>

**Graceful wholebody pick-and-place for mobile manipulator**
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei</div> <div style="float:right; text-align:right"><i>2022.10 - 2022.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen</p>
<ul>
<li>
  <p>Train GGCNN for the perception of the objects' pose and the grasp quality. The inputs of GGCNN are pointclouds while the outputs are the grasp quality, width and orientation.</p>
</li>
<li>
  <p> Jointly consider the manipulability, energy, manipulator orientation and path tracking in the QP solvers. The dynamic-weighted QP is implemented based on the tracking error to achieve graceful picking-and-placing.</p>
</li>
</ul>

**Calibration and fusion of multi-sensors**
<div style="float:left; text-align:left">China-Singapore International Joint Research Institute, Guangzhou</div> <div style="float:right; text-align:right"><i>2021.12 - 2022.02</i></div>
<br/>
<ul>
<li>
  <p> Synchronize and rectify the multimodal information collected from the LIDAR-RGB-IR suite. Calibrate the intrinsics and extrinsics of different sensors.</p>
</li>
<li>
  <p> Train YOLO V5 on the COCO dataset for 2D target detection, based on which the 3D pointclouds segmentation and classification are used to evaluate the 3D position.</p>
</li>
</ul>

## Honor & Awards

<ul>
<li> <div style="float:left; text-align:left">National Scholarship</div> <div style="float:right; text-align:right"><i>2021-10</i></div></li>

<li> <div style="float:left; text-align:left"> Scholarship of <a href="https://www.gac.com.cn/cn/" title="GuangQi">Guangzhou Automobile Group Co., Ltd</a></div> <div style="float:right; text-align:right"><i>2020-10</i></div></li>
<li> <div style="float:left; text-align:left">National Scholarship</div> <div style="float:right; text-align:right"><i>2019-10</i></div></li>
<li> <div style="float:left; text-align:left">The first prize of the <a href="https://www.caa.org.cn/Content/260.html" title="zhinengche">National University Students Intelligent Car Race</a> </div> <div style="float:right; text-align:right"><i>2020-08</i></div></li>
<li> <div style="float:left; text-align:left">Meritorious Winner of  <a href="https://www.comap.com/contests/mcm-icm" title="zhinengche">Interdisciplinary Contest In Modeling (ICM)</a> </div> <div style="float:right; text-align:right"><i>2021-03</i></div> </li>
</ul>



## Skills

**Programming and Learning Framework:**
<p>Python, MATLAB, C/C++, PyTorch, Pybullet</p>  

**Robotics:**
<p>DH, wholebody control, Admittance/Impedance Control, Gravity Compensation,  Shared control, teleoperation</p>

**Hardware Experience:**
<p>Franka, UR10, Mobile Manipulator, Robotiq 2F85, Vicon, Touch X, ATI sensors, STM32</p>
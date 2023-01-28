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

My research interests are robotic learning from demonstration, mobile manipulation and whole-body control. Specifically, I have been exploring and exploiting the potentiality of the wheeled mobile manipulators in acquiring manipulation skills from human demonstration, such as picking-and-placing or openning the door. Recently I am working on the wholebody control of the wheeled mobile maniputors through SLQ-MPC controller implemented in [OCS2](https://github.com/leggedrobotics/ocs2). This goal of this project is to enable mobile manipulators to plan and execute the manipulation in real time in a cluttered environment.

## Education
**South China University of Technology**
<div style="float:left; text-align:left"><i>Master, Robotics</i></div> <div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br />
<div style="float:left; text-align:left">School of Automation Science and Engineering, South China University
of Technology</div>
<p><br />Supervisor: Prof. Chenguang Yang</p>

**South China University of Technology**
<div style="float:left; text-align:left"><i>Bachelor, Department of Automation</i></div> 
<div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div><br/>

## Research Experiences


**Realtime wholebody control of the mobile manipulator in cluttered environment**
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei</div> <div style="float:right; text-align:right"><i>2022.10 - present</i></div>  
<br />
Advisor: Dr. Chen Chen</br>
<ul>
<li>
   Construct the occupancy grid map and ESDF based on <a href="https://github.com/HKUST-Aerial-Robotics/FIESTA" title="FIESTA">FIESTA</a>. Then bias the sample of RRT* to get an initial guiding path according to the topological map in Cartesian space. 
</li>
<li>
  <p> Propose and analyse the adaptive MPC theorectically to improve the convergence and optimality in complex environments where multiple non-convex costs or contraints exist</p>
</li>
<li>
  <p>The proposed framework is verified through experiments about picking and placing a cup gracefully in clutted environment.</p>
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

## Skills
---
**Programming and Machine Learning Framework:**
<p>Python, MATLAB, C/C++, PyTorch.</p>  

**Simulator:**
<p>MuJoCo, PyBullet, Gazebo.</p>

**Hardware Experience:**
<p>Franka, UR10, Mobile Manipulator, Robotiq 2F85, Vicon</p>
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

My research interests are **wholebody planning and control** for different robots such as **mobile manipulator, multicopter and car**. Specifically, I have been exploring and exploiting the potentiality of the wheeled mobile manipulators to avoiding collision aggressively in a wholebody manner and finishing pick-and-place task in 3d cluttered dynamic environment. Besides, I am working towards the low-cost and efficient mapping, planning and control framework for **multicopter** in unstructed environment. I have sufficient engineering experience on deploying algorithms in various robotic scenarios such as agile collision avoidance, pedestrian following and picking-placing. The goal of my research is to endow robots with **agile mobility and manoeuvrability** in a 3d cluttered **dynamic** environment.

## Education and Working
**South China University of Technology**
<div style="float:left; text-align:left"><i>Master, Robotics</i></div> <div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br />
<div style="float:left; text-align:left">School of Automation Science and Engineering</div>
<p><br />Supervisor: Prof. Chenguang Yang</p>

**South China University of Technology**
<div style="float:left; text-align:left"><i>Bachelor, School of Automation Science and Engineering</i></div> 
<div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div><br/>
<p>GPA: 3.94/4.0 (ranked first)</p>

**Huawei Technologies Co.Ltd**
<div style="float:left; text-align:left"><i>Intern, Application Innovation Laboratorys</i></div> 
<div style="float:right; text-align:right"><i>June. 2022 - now</i></div><br/>
<p>Planning and Control for various robots</p>

**[FastLab](http://zju-fast.com/) of Zhejiang University**
<div style="float:left; text-align:left"><i>Visiting Student of FastLab, supervised by Prof. <a href="http://zju-fast.com/fei-gao
">Fei Gao</a></i></div> 
<div style="float:left; text-align:left"><i>Oct. 2023 - Nov. 2023</i></div> 

## Research Experiences


**RAMPAGE: Towards Whole-body, Real-Time and Agile Motion Planning in Dynamic Cluttered Environments for Mobile Manipulators**
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei</div> <div style="float:right; text-align:right"><i>2022.10 - present</i></div>  
<br />
Advisor: Dr. Chen Chen
<ul>
<li>
    A novel hierarchical topology-guided searching method for the MMs is developed to find an initial whole-body kinodynamic trajectory in real time (30ms).
</li>
<li>
  <p> We derive and implement a whole-body trajectory optimization method which naturally integrates the planning and control module (IPC) in an augmented Lagrangian differential dynamic programming (AL-DDP) form.</p>
</li>
<li>
  <p>We make use of a real-time constructed ESDF map to achieve low-cost high-speed collision calculation against dynamic obstacles in batch, with the MM body being approximated by sphere decomposition.</p>
</li>
</ul>

**Learning the coordination motion of mobile manipulators through human demonstration**
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

**Low-cost and effient mapping, planning (SE3) and control for multicopter in embedded system**
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei. FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - 2023.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen. Dr. Zehui Meng. Prof. Fei Gao</p>
<ul>
<li>
  <p> 基于两个特性的建图.NPU加速</p>
</li>
<li>
  <p> IPC+RCESDF+MPCC</p>
</li>
<li>
  <p> 凸包+MINCO实现SE3</p>
</li>
</ul>
**Pedestrian following and collision avoidance with spatial-temporal optimization for differential car **
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei. FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - 2023.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen. Dr. Zehui Meng. Prof. Fei Gao</p>
<ul>
<li>
  <p> Astar</p>
</li>
<li>
  <p> 视角跟随滤波</p>
</li>
<li>
  <p> 时空联合优化</p>
</li>
</ul>
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
<p>Python, MATLAB, C/C++, PyTorch, Pybullet, Airsim, Embedded System</p>  

**Robotics:**
<p>Wholebody control, Peception and mapping, Convex Optimization, Admittance/Impedance Control, Gravity Compensation, teleoperation</p>
**Hardware Experience:**
<p>Multicopter, <a href="https://en.directdrive.com/">Diablo</a> Franka, UR, Mobile Manipulator, Robotiq 2F85, Vicon, Touch X, ATI sensors, STM32</p>
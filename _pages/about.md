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

I am Yuqiang Yang, a master student at [South China University of Technology](https://www.scut.edu.cn/new/), supervised by [Prof. Chenguang Yang](https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao). My research interests are to explore and exploit the potentiality of various robots, such as **mobile manipulator, autonomous car and multicopter**, to perform tasks autonomously and efficiently in unstructured environment. 
<!-- The goal of my research is to endow robots with **agile mobility and manoeuvrability** in a 3d cluttered **dynamic** environment. -->
   
Specifically, I have explored and realized the posibility of allowing the mobile manipulators to efficiently pick and place in a **wholebody** manner while avoidance collision smoothly **in cluttered dynamic environment** full of chairs, tables and shelves. Besides, I am working towards the low-cost and accurate state estimation (Visual Inertial Odometry) , mapping (Occupancy Grid Map and Euclidean Signed Distance Field), planning and control (SE3) framework for **quadrotor** in complex environments. For **autonomous car** with non-holonomic constraints, I investigated the **real-time** perception, mapping and collision-free motion planning to follow and serve the target person well. I have sufficient engineering experience on deploying algorithms in various robotic scenarios such as environmental reconstrunction, household service and car racing, etc. 

## Education and Trainning

<div style="float:left; text-align:left"><i><b>South China University of Technology</b></i></div> <div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br />
<p>Master, Robotics</p>
<p>Supervisor: Prof. <a href="https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao">Chenguang Yang</a></p>
<p>GPA: 3.82/4.0 (ranked first)</p>

**South China University of Technology**
<div style="float:left; text-align:left"><i>Bachelor, Automation</i></div> <br/>
<div style="float:left; text-align:left">School of Automation Science and Engineering</div>
<div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div><br/>
<p>GPA: 3.94/4.0 (ranked first)</p>


**[FastLab](http://zju-fast.com/) of Zhejiang University**
<div style="float:left; text-align:left"><i>Visiting Student</i></div> 
<div style="float:right; text-align:right"><i>Oct. 2023 - Nov. 2023</i></div> <br/>
<div style="float:left; text-align:left">Wholebody planning and precise control for multicopter</div>
<p><br />Supervisor: Prof. <a href="http://zju-fast.com/fei-gao
">Fei Gao</a></p>




## Research Experiences

<div style="float:left; text-align:left"> <b>RAMPAGE: Towards Whole-body, Real-Time and Agile Motion Planning in Dynamic Cluttered Environments for Mobile Manipulators</b>  <a href="https://yuqiang-yang.github.io/publications#rampage">Video</a>,  <a href="https://github.com/yuqiang-yang/TIE-Supplementary-video">PDF</a> <div style="float:right; text-align:right"><i>2022.10 - 2023.12</i></div>  
<p>Accepted to IEEE Transaction on Industrial Electronics</p>
<p>Advisor: Dr. Chen Chen, Dr. <a href="https://scholar.google.com.hk/citations?user=yO5K6xwAAAAJ&hl=th">Zehui Meng</a></p>
<ul>
<li>
    A novel <b>hierarchical topology-guided</b> searching method for the MMs is developed to find an initial whole-body kinodynamic trajectory in real time (30ms), striking the balance in the success rate and the efficiency.
</li>
<li>
  <p> We derive and implement a whole-body trajectory optimization method which naturally <b>integrates the planning and control module</b> (IPC) in an augmented Lagrangian differential dynamic programming (AL-DDP) form.</p>
</li>
<li>
  <p>We make use of a <b>real-time constructed ESDF map</b> to achieve low-cost high-speed collision calculation against dynamic obstacles in batch, with the MM body being approximated by <b>sphere decomposition</b>.</p>
</li>
<li>
Benchmark
comparisons and extensive experiments demonstrate that
the proposed framework can plan whole-body collision-free
trajectories in real-time with a high success rate and accurately execute them at an <b>average speed of 1.86m/s</b> among
dynamic obstacles with a maximum speed of 2m/s.
</li>
</ul>

<div style="float:left; text-align:left"><b>Learn to Coordinate: a Whole-Body Learning from Demonstration Framework for Differential Drive Mobile Manipulators</b> <a href="https://yuqiang-yang.github.io/publications#open_door">Video1</a>, <a href="https://yuqiang-yang.github.io/publications#learning">Video2</a>, <a href="https://ieeexplore.ieee.org/abstract/document/10394442">PDF</a> <div style="float:right; text-align:right"><i>2022.04 - 2022.09</i></div>
<p> 
Advisor: Prof. Chenguang Yang</p>
<ul>
<li>
  <p>Propose a
whole-body learning from demonstration framework through <b>Gaussian Process</b>, which
endows the mobile manipulator’s skill learning process with
features of large-scale convergence, coordination working and
disturbance rejection, after just <b>a few human demonstrations</b>.</p>
</li>
<li>
  <p>An
efficient kinesthetic teaching method is devised based on the
<b>weighted least-norm (WLN)</b> inverse kinematics solution and an
admittance controller, which facilitates human users to guide
the mobile manipulator to perform tasks.</p>
</li>
<li>
  <p> The framework allows for human-in-the-loop correction when the whole-body is conducting a task.</p>
</li>
<li>
  <p> We also implement a model-based and efficient <b>door openning</b> for mobile manipulator, even under <b>random disturbance</b>.</p>
</li>
</ul>

## Project Experiences

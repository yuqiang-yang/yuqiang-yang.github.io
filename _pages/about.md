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

<div style="float:left; text-align:left"><i><b>South China University of Technology</b></i></div> <div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br/>
<p>Master, Robotics</p>
Supervisor: Prof. <a href="https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao">Chenguang Yang</a>
</br>GPA: 3.82/4.0 (ranked first)
</br>
</br>
<div style="float:left; text-align:left"><i><b>South China University of Technology</b></i></div> <div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div> <br/>
<p> Bachelor of Engineering, Automation</p>
</br> School of Automation Science and Engineering
<p>GPA: 3.94/4.0 (ranked first)</p>
</br>
<div style="float:left; text-align:left"><i><b> <a href="http://zju-fast.com/fei-gao">FastLab</a> of Zhejiang University</b></i></div> <div style="float:right; text-align:right"><i>Oct. 2023 - Nov. 2023</i></div> 
</br> Visiting student
</br> Wholebody planning and precise control for multicopter
<br />Supervisor: Prof. <a href="http://zju-fast.com/fei-gao
">Fei Gao</a>


## Research Experiences

<div style="float:left; text-align:left"> <b>RAMPAGE: Towards Whole-body, Real-Time and Agile Motion Planning in Dynamic Cluttered Environments for Mobile Manipulators</b>  <a href="https://yuqiang-yang.github.io/publications#rampage">Video</a>,  <a href="https://github.com/yuqiang-yang/TIE-Supplementary-video">PDF</a></div> <div style="float:right; text-align:right"><i>2022.10 - 2023.12</i></div>  
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

<div style="float:left; text-align:left"><b>Learn to Coordinate: a Whole-Body Learning from Demonstration Framework for Differential Drive Mobile Manipulators</b> 
<a href="https://yuqiang-yang.github.io/publications#open_door">Video1</a>, <a href="https://yuqiang-yang.github.io/publications#learning">Video2</a>, <a href="https://ieeexplore.ieee.org/abstract/document/10394442">PDF</a></div> <div style="float:right; text-align:right"><i>2022.04 - 2022.09</i></div>
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

**Low-cost and effient location, mapping, planning and control for multicopter in embedded system** 
<a href="https://yuqiang-yang.github.io/talks#planning">Video1</a>, <a href="https://yuqiang-yang.github.io/talks#hover">Video2</a>, <a href="https://yuqiang-yang.github.io/talks#rcesdf">Video3</a>

<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei; FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - present</i></div>
<p> <br />
Advisor: Dr. Chen Chen; Dr. <a href="https://scholar.google.com.hk/citations?user=yO5K6xwAAAAJ&hl=th">Zehui Meng</a>; Prof. <a href="https://scholar.google.com.hk/citations?user=4RObDv0AAAAJ&hl=zh-CN">Fei Gao</a></p>
<ul>
<li>
 <p> The VIO is improved from <a href="https://github.com/HKUST-Aerial-Robotics/VINS-Fusion">Vins-Fusion</a> to achieve best performance in a low-performance chip. The front-end feature extraction part is changed to a <b>learning-based feature </b><a href="https://github.com/facebookresearch/silk">Silk</a>, boosting the computation efficiency though an <b>nerual processing unit (NPU)</b>. The back-end combines the filter-based and optimization-based methods to strike a good balance between the computation efficency and the location precision. </p>
</li>
<li>
  <p> We design and implement a low-cost efficient occupancy grid map (OGM) updating algorithm with the features of <b>incremental inflation</b> and <b>spatial-temporal sliding windows</b>. This enables a fast occupancy infomation update in large environment.</p>
</li>

<li>
  <p> A <b>robot-centric ESDF</b> (RC-ESDF) is utilized to represent the collision cost in the back-end optimization of our model prediected contour control (MPCC). This <b>lazy evaluation strategy</b> saves many times and calculations, allowing to plan and excute agressive trajectory in unknown environment.</p>
</li>

</ul>

**SE3 planning and control for multicopter to cross narrow gap** 
<a href="https://yuqiang-yang.github.io/talks#se3">Video</a>

<div style="float:left; text-align:left"> FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - present</i></div>
<p> <br />
Advisor:  Prof. <a href="https://scholar.google.com.hk/citations?user=4RObDv0AAAAJ&hl=zh-CN">Fei Gao</a></p>
<ul>
<li>
 <p> We also construct a <b>safe flight corridor</b> (SFC) consisting of many convex polytopes. Then <a href="https://github.com/ZJU-FAST-Lab/GCOPTER">MINCO</a> trajectory will be optimized and executed with a finely tuned controller considering the <b>full dynamics</b> to make the multicoter cross a narrow gap. </p>
</li>
<li>
  <p> We design and implement a low-cost efficient occupancy grid map (OGM) updating algorithm with the features of <b>incremental inflation</b> and <b>spatial-temporal sliding windows</b>. This enables a fast occupancy infomation update in large environment.</p>
</li>

</ul>

**Pedestrian following and collision avoidance with spatial-temporal optimization for differential car** <a href="https://yuqiang-yang.github.io/teaching#follow">Video</a>

<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei. FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - 2023.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen. Dr. Zehui Meng. Prof. Fei Gao</p>
<ul>
<li>
  <p> A multi-level hybrid A* algorithm is used to find intial kinodynamic trajecory to the future position (predicted by EKF) in a certain horizon. It considers the <b>object occlusion, uncertainty and collision</b> simultaneously.</p>
</li>
<li>
  <p> We filter the object pointcloud of OUSTER lidar based on the bounding box generated by the visual perception. After then, the regristerd pointcloud by Fast-Lio2 will be considered as obstacles.</p>
</li>
<li>
  <p> The initial trajectory parameterized by MINCO is optimized <b>spatially and temporally</b>. A low-level MPC considering the kinematics and communication delay is implemented to accurately track the planning trajecoty.</p>
</li>
</ul>

**Self-balanced smart car with wireless charging capability** <a href="https://yuqiang-yang.github.io/teaching#balance">Video</a>
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
  <p> We finished the race in fifth national ranking with a time of 23.8s and won the <b>first prize</b>.</p>
</li>
</ul>

**Graceful wholebody pick-and-place for mobile manipulator** <a href="https://yuqiang-yang.github.io/talks#pick_and_place">Video</a>
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei</div> <div style="float:right; text-align:right"><i>2022.10 - 2022.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen</p>
<ul>
<li>
  <p>Train <a href="https://github.com/dougsm/ggcnn">GGCNN</a>  for the perception of the objects' pose and the grasp quality. The inputs of GGCNN are pointclouds while the outputs are the grasp quality, width and orientation.</p>
</li>
<li>
  <p> Jointly consider the manipulability, energy, manipulator orientation and path tracking in the QP solvers. The <b>dynamic-weighted QP</b> is implemented based on the tracking error to achieve graceful picking-and-placing.</p>
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


## Internship
**Huawei Technologies Co.Ltd**
<div style="float:left; text-align:left"><i>Intern, Application Innovation Laboratorys</i></div> 
<div style="float:right; text-align:right"><i>June. 2022 - now</i></div><br/>
<div style="float:left; text-align:left">Planning and Control for various robots</div>
<p><br />Supervisor: Dr. Chen Chen, Dr. Zehui Meng</p>

## Skills

**Programming:**
<p>Python, MATLAB, C/C++, PyTorch, Pybullet, Airsim, Embedded System</p>  

**Robotics:**
<p>Wholebody control, Peception and mapping, Convex Optimization, Admittance/Impedance Control, Gravity Compensation, teleoperation</p>

**Hardware Experience:**
<p>Multicopter, <a href="https://en.directdrive.com/">Diablo</a>, Franka, UR, Mobile Manipulator, Robotiq 2F85, Vicon, Touch X, ATI sensors, STM32</p>## Internship
**Huawei Technologies Co.Ltd**
<div style="float:left; text-align:left"><i>Intern, Application Innovation Laboratorys</i></div> 
<div style="float:right; text-align:right"><i>June. 2022 - now</i></div><br/>
<div style="float:left; text-align:left">Planning and Control for various robots</div>
<p><br />Supervisor: Dr. Chen Chen, Dr. Zehui Meng</p>
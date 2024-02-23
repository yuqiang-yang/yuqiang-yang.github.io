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
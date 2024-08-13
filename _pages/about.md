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

I am Yuqiang Yang, a master student at [South China University of Technology](https://www.scut.edu.cn/new/), supervised by [Prof. Chenguang Yang](https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao). My research interests are to explore and exploit the potentiality of various robots, such as **mobile manipulator, autonomous car, humanoid and multicopter**, to perform tasks autonomously and efficiently in unstructured environment. 
<!-- The goal of my research is to endow robots with **agile mobility and manoeuvrability** in a 3d cluttered **dynamic** environment. -->
   
Specifically, I have explored and realized the possibility of allowing the mobile manipulators to efficiently pick and place in a **wholebody** manner while avoidance collision smoothly **in cluttered dynamic environment** full of chairs, tables and shelves. Besides, I am working towards the low-cost and accurate state estimation (Visual Inertial Odometry) , mapping (Occupancy Grid Map and Euclidean Signed Distance Field), planning and control (SE3) framework for **quadrotor** in complex environments. For **autonomous car** with non-holonomic constraints, I investigated the **real-time** perception, mapping and collision-free motion planning to follow and serve the target person well. In the field of robotics learning, I study how to utilize the Nvidia Isaac Lab environment for Unitree H1 humanoid locomotion task. I have sufficient engineering experience on deploying algorithms in various robotic scenarios such as environmental reconstruction, household service and car racing, etc. 

## Education and Training


<div style="float:left; text-align:left; line-height: 1.8">
<i><b>South China University of Technology</b></i>
<br>Master, Robotics
<br>Supervisor: Prof. <a href="https://scholar.google.com/citations?user=e8io0fYAAAAJ&hl=zh-CN&oi=ao">Chenguang Yang</a>
<br> GPA: 3.82/4.0 (ranked first)
</div>
<div style="float:right; text-align:right"><i>Sep. 2022 - Present</i></div><br/>
<br/> <br/>
<br/>

<div style="float:left; text-align:left; line-height: 1.8">
<i><b>South China University of Technology</b></i>
<br>Bachelor of Engineering, Automation
<br>School of Automation Science and Engineering
<br>GPA: 3.94/4.0 (ranked first)
</div> <div style="float:right; text-align:right"><i>Sep. 2018 - Jun. 2022</i></div> <br/>

<br/>
<br/>
<br/>


<div style="float:left; text-align:left; line-height: 1.8">
<i><b> <a href="http://zju-fast.com/fei-gao">FastLab</a> of Zhejiang University</b></i>
<br>Visiting student
<br>Wholebody planning and  control for multicopter
<br>Supervisor: Prof. <a href="http://zju-fast.com/fei-gao">Fei Gao</a>
</div>
 <div style="float:right; text-align:right"><i>Oct. 2023 - Nov. 2023</i></div> <br/>
<br/>
<br/>


## Research Experiences

<div style="float:left; text-align:left"> <b>RAMPAGE: Towards Whole-body, Real-Time and Agile Motion Planning in Dynamic Cluttered Environments for Mobile Manipulators</b>  [<a href="https://yuqiang-yang.github.io/publications#rampage">Video</a>,  <a href="https://github.com/yuqiang-yang/TIE-Supplementary-video">PDF</a>]</div> <div style="float:right; text-align:right"><i>2022.10 - 2023.12</i></div>  
<p>Accepted to IEEE Transaction on Industrial Electronics</p>
<p>Advisor: Dr. Chen Chen, Dr. <a href="https://scholar.google.com.hk/citations?user=yO5K6xwAAAAJ&hl=th">Zehui Meng</a></p>
<ul>
<li>
    Developed a novel <b>hierarchical topology-guided</b> searching method to find whole-body kinodynamic trajectories in real time (≈30ms), striking good balance in the success rate and the efficiency.
</li>
<li>
  <p> Derived and implemented a whole-body trajectory optimization method which naturally <b>integrates the planning and control module</b> (IPC) in an augmented Lagrangian differential dynamic programming (AL-DDP) form.</p>
</li>
<li>
  <p>Utilized a <b>real-time constructed ESDF map</b> and a novel sphere decomposition for mobile manipulator to achieve one-shot collision detection against dynamic obstacles in batch.</p>
</li>
<li>
Conducted extensive experiments to demonstrate the effectiveness of our framework in planning and executing whole-body collision-free
trajectories with a high success rate (≈80%) and a excellent tracking accuracy among highly dynamic obstacles.
</li>
</ul>
<center>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="gif" style="width: 40%; height: auto; padding: 5px;">
      <img src="../files/esdf.gif" alt="GIF 1" width="960" height="200" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
    <div class="gif" style="width: 40%; height: auto; padding: 5px;">
      <img src="../files/planning.gif" alt="GIF 2" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/realwolrd.gif" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>
  </center>

<div style="float:left; text-align:left"><b>Learn to Coordinate: a Whole-Body Learning from Demonstration Framework for Differential Drive Mobile Manipulators</b> 
[<a href="https://yuqiang-yang.github.io/publications#open_door">Video1</a>, <a href="https://yuqiang-yang.github.io/publications#learning">Video2</a>, <a href="https://ieeexplore.ieee.org/abstract/document/10394442">PDF</a>]</div> <div style="float:right; text-align:right"><i>2022.04 - 2022.09</i></div>
<p> 
Accepted to 2023 IEEE Conference on Systems, Man, and Cybernetics </p>
<p> 
Advisor: Prof. Chenguang Yang</p>
<ul>
<li>
  <p>Proposed a
whole-body learning from demonstration framework through <b>Gaussian Process</b>, which
endows the mobile manipulator’s skill learning process with
features of coordination working and
disturbance rejection, after just <b>a few human demonstrations</b>.</p>
</li>
<li>
  <p> Devised an efficient kinesthetic teaching method based on the <b>weighted least-norm (WLN)</b> inverse kinematics solution and an admittance controller, which facilitates human users to guide the mobile manipulator to perform tasks.</p>
</li>
<li>
  <p> Implemented a model-based and robust <b>door opening</b> algorithm for mobile manipulator in a coordinated whole-body manner, even under <b>random disturbance</b>.</p>
</li>
</ul>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/open_door.gif" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>

## Project Experiences

**Locomotion in complex terrain through reinforcement learning in Isaac lab** 
[<a href="https://yuqiang-yang.github.io/talks#se3">Video</a>]

<div style="float:left; text-align:left"> Learning in progree</div> <div style="float:right; text-align:right"><i>2024.6 - present</i></div>
<p> <br />
<ul>
<li>
 <p> Designed and fine-tuned the reward function for humanoid locomotion. Then implemented proximal policy optimization algorithm (PPO) to train the humanoid locomotion from curriculum.
 </p>
</li>
<li>
<p> Sim-to-Sim transfer the learned policy into different photo-realistic environments of Nvidia Isaac Sim. Demonstrate robust locomotion ability of the RL policy for Unitree H1.</p>
</li>
</ul>
<!-- <center>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="gif" style="width: 40%; height: auto; padding: 5px;">
      <img src="../files/h1-hosp.gif" alt="GIF 1" width="960" height="200" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
    <div class="gif" style="width: 40%; height: auto; padding: 5px;">
      <img src="../files/h1-office.gif" alt="GIF 2" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="gif" style="width: 40%; height: auto; padding: 5px;">
      <img src="../files/h1-out.gif" alt="GIF 1" width="960" height="200" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
    <div class="gif" style="width: 40%; height: auto; padding: 5px;">
      <img src="../files/h1-stair.gif" alt="GIF 2" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>
  </center> -->

**Low-cost and efficient location, mapping, planning and control for multicopter in embedded system** 
[<a href="https://yuqiang-yang.github.io/talks#planning">Video1</a>, <a href="https://yuqiang-yang.github.io/talks#hover">Video2</a>, <a href="https://yuqiang-yang.github.io/talks#rcesdf">Video3</a>]

<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei; FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - 2024.3</i></div>
<p> <br />
Advisor: Dr. Chen Chen; Dr. <a href="https://scholar.google.com.hk/citations?user=yO5K6xwAAAAJ&hl=th">Zehui Meng</a>; Prof. <a href="https://scholar.google.com.hk/citations?user=4RObDv0AAAAJ&hl=zh-CN">Fei Gao</a> </p>
<ul>
<li>
 <p> Improved <a href="https://github.com/HKUST-Aerial-Robotics/VINS-Fusion">Vins-Fusion</a> by replacing front-end feature extraction with a <b>learning-based feature </b> and enhancing back-end optimization with a QR-based dimensionality reduction algorithm. Boosted the accuracy and robustness greatly in low-performance chip.</p>
</li>
<!-- <a href="https://github.com/facebookresearch/silk">Silk</a> 
, boosting the computation efficiency though an <b>nerual processing unit (NPU)</b>.-->
<li>
  <p> Implemented a low-cost efficient occupancy grid map (OGM) updating algorithm based on <b>incremental inflation</b> and <b>spatial-temporal sliding windows</b>, which enables a extremely fast occupancy information update in large environments.</p>
</li>

<li>
  <p> Utilized the <b>robot-centric ESDF</b>, whose values are only lazily evaluated in the local frame for extraordinarily small calculations, to formulate the collision cost in the back-end optimization of model predicted contour control (MPCC).</p>
</li>

</ul>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/fly_forest.gif" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>

**SE3 planning and control for multicopter to cross narrow gap** 
[<a href="https://yuqiang-yang.github.io/talks#se3">Video</a>]

<div style="float:left; text-align:left"> FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.10 - 2023.12</i></div>
<p> <br />
Advisor:  Prof. <a href="https://scholar.google.com.hk/citations?user=4RObDv0AAAAJ&hl=zh-CN">Fei Gao</a></p>
<ul>
<li>
 <p> Constructed the <b>safe flight corridor</b> (SFC) including a series of mutually-consecutive convex polytopes to represent the free space of the quadrotor.
 </p>
</li>
<li>
<p> Utilized <a href="https://github.com/ZJU-FAST-Lab/GCOPTER">MINCO</a> to parameterize the trajectory in <b>spatial-temporal space</b> and jointly optimize a crossing-gap trajectory for better smoothness, using L-BFGS algorithm.</p>
</li>
<li>
  <p> Identified the quadrotor dynamics parameter for a accurate <b>thrust mapping</b> w.r.t the battery voltage and control duty cycle. Then finely tuned the controller to track the large-attitude trajectory to cross the narrow gap.</p>
</li>

</ul>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/se3.jpg" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>

**Pedestrian following and collision avoidance with spatial-temporal optimization for differential car** [<a href="https://yuqiang-yang.github.io/teaching#follow">Video</a>]

<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei. FastLab, Zhejiang University</div> <div style="float:right; text-align:right"><i>2023.2 - 2023.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen. Dr. Zehui Meng. Prof. Fei Gao</p>
<ul>
<li>
  <p> Proposed a multi-level hybrid A* algorithm to find kinodynamic trajectory to the future position (predicted by EKF) in a certain horizon,jointly considering the <b>object occlusion, uncertainty and collision</b> simultaneously.</p>
</li>
<li>
  <p> Filtered the object pointcloud of OUSTER lidar based on the bounding box generated from the visual perception and registered the remaining pointcloud of <b>Fast-Lio2</b> as obstacles.</p>
</li>
<li>
  <p> Optimized the trajectory parameterized by MINCO  <b>spatially and temporally</b> using L-BFGS. Then implemented a low-level MPC controller to accurately track the trajectories under kinematics constraints and communication delay.</p>
</li>
</ul>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/follow.gif" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>

**Self-balanced racing car with wireless charging capability** [<a href="https://yuqiang-yang.github.io/teaching#balance">Video</a>]
<div style="float:left; text-align:left">School of Automation Science and Engineering, SCUT</div> <div style="float:right; text-align:right"><i>2020.01 - 2020.08</i></div>
<p> <br />
Advisor: Dr. An Chen</p>
<ul>
<li>
  <p>Designed and implemented the adaptive wireless-charging algorithm (PD) to quickly charge (≈30W) the super-capacitors mounted on the car. </p>
</li>
<li>
  <p> Tuned a cascade position, velocity, attitude and angular controller for a two-wheeled car to race on the track and pass various elements (including circle, slope, crossroads, etc) correctly and steadily.</p>
</li>
<li>
  <p> Finished the race with the fifth national place in 23.8s and won the first prize.</p>
</li>
</ul>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/racing.png" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>

**Wholebody pick-and-place for mobile manipulator** [<a href="https://yuqiang-yang.github.io/talks#pick_and_place">Video</a>]
<div style="float:left; text-align:left">Application Innovate Laboratory, Huawei</div> <div style="float:right; text-align:right"><i>2022.10 - 2022.11</i></div>
<p> <br />
Advisor: Dr. Chen Chen</p>
<ul>
<li>
  <p>Trained <a href="https://github.com/dougsm/ggcnn">GGCNN</a>  for the 6-D perception of the objects, whose inputs are camera pointcloud and outputs are the grasp quality, width and orientation.</p>
</li>
<li>
  <p> Utilized OSQP to solved the dynamic-weighted QP problem, which jointly considers the manipulability, energy, manipulator orientation and path tracking to achieve coordinated picking-and-placing in wholebody manner.</p>
</li>
</ul>
  <div class="gif-container" style="display: flex;justify-content: center; align-items: center; flex-wrap: wrap;">
    <div class="long-gif" style="width: 80%; height: auto; padding: 5px;">
      <img src="../files/pick_place.gif" alt="Long GIF" style="width: 100%; height: 100%; object-fit: contain;">
    </div>
  </div>

## Honor & Awards

<ul>
<li> <div style="float:left; text-align:left">National Scholarship</div> <div style="float:right; text-align:right"><i>2021-10</i></div></li>

<li> <div style="float:left; text-align:left"> Scholarship of <a href="https://www.gac.com.cn/cn/" title="GuangQi">Guangzhou Automobile Group Co., Ltd</a></div> <div style="float:right; text-align:right"><i>2020-10</i></div></li>
<li> <div style="float:left; text-align:left">National Scholarship</div> <div style="float:right; text-align:right"><i>2019-10</i></div></li>
<li> <div style="float:left; text-align:left">The first prize of the <a href="https://www.caa.org.cn/Content/260.html" title="zhinengche">National University Students Intelligent Car Race</a> </div> <div style="float:right; text-align:right"><i>2020-08</i></div></li>
<li> <div style="float:left; text-align:left">Meritorious Winner of  <a href="https://www.comap.com/contests/mcm-icm" title="zhinengche">Interdisciplinary Contest In Modeling (ICM)</a> </div> <div style="float:right; text-align:right"><i>2021-03</i></div> </li>
</ul>


## Internship

<div style="float:left; text-align:left; line-height: 1.8">
<i><b> Huawei Technologies Co.Ltd</b></i>
<br>Intern, Application Innovation Laboratorys
<br>Planning and Control for various robots
<br>Supervisor: Dr. Chen Chen, Dr. Zehui Meng
</div>
 <div style="float:right; text-align:right"><i>June. 2022 - now</i></div> <br/>
<br/>
<br/>
<br/>

<div style="float:left; text-align:left; line-height: 1.8">
<i><b>China-Singapore International Joint Research Institute</b></i>
<br>Intern, Robot Perception and Computer Vision Group
<br>Multi-sensor calibration and 3D detection
<br>Supervisor: Dr. Mingxing Wen
</div>
 <div style="float:right; text-align:right"><i>Jan. 2021 - Mar. 2021</i></div> <br/>
<br/>
<br/>



## Skills

**Programming:**
<p>Python, MATLAB, C/C++, PyTorch, Pybullet, Airsim, Embedded System</p>  

**Robotics:**
<p>Wholebody control, Peception and mapping, Convex Optimization, Admittance/Impedance Control, Gravity Compensation, teleoperation</p>

**Hardware Experience:**
<p>Multicopter, <a href="https://en.directdrive.com/">Diablo</a>, Franka, UR, Mobile Manipulator, Robotiq 2F85, Vicon, Touch X, ATI sensors, STM32</p>
<div align="center"> <h1> Automated Material Transfer </h1> <br/>
 Stewart Lamon <br/> Yardley Ordonez <br/> Zahory Ramirez <br/> Nolan Spencer <br/><br/>
<img src = "PR/Pictures/Chico emblem.png" height = "360px" style="margin:10px 10px"> <br/>
MECA 470 <br/> Fall 2020 <br/>
</div> <br/>

## Introduction 
The objective of this project was to simulate an Unmanned Ground Vehicle (UGV) that would be able to transfer material to different set of locations. To complete this simulation, Robot Operating System (ROS) Kinetic was utilized as the base environment for simulating an autonomous UGV. This group chose to emulate Clearpath Robotics' 
<a href="https://clearpathrobotics.com/warthog-unmanned-ground-vehicle-robot/">Warthog UGV</a> 
and their 
<a href="http://www.clearpathrobotics.com/assets/guides/melodic/warthog/">online tutorials</a>. 
There were other software toolkits that were utilized for this project, and there will be further explanation of these toolkits.
<br/><br/>

<div align="center">
<img src = "PR/Pictures/Warthog picture.jpg" height = "360px" style="margin:10px 10px"> 
<br/><br/>  
</div>

Clearpath Robotics’ Warthog UGV was chosen due to its many features that would allow for it to be utilized in moderate weather conditions, max payload of 600 lbs and towing capacity of 1984 lbs. Another aspect that caught the attention of this group, was that it uses a 64-bit version of Ubuntu 16.04 or 18.04 LTS. The Warthog's onboard computer comes with ROS kinetic or melodic distribution preinstalled and configured.

## Software 
Below there will be a of list of the software empoyed for this project with their respective links for downloading or acquiring more information: <br/>

<ul>
 <li>Virtual Machine</li>
 <ul>
  <li><a href="https://www.virtualbox.org/wiki/Downloads">Oracle Virtualbox</a></li>
 </ul> <br/>
 
 <li>Linux Operating System</li>
 <ul>
 <li><a href="https://releases.ubuntu.com/16.04/">Ubuntu 16.04 LTS</a></li> 
 </ul> <br/>
 
 <li>ROS Distribution</li>
 <ul>
  <li><a href="http://wiki.ros.org/kinetic">Kinetic Kame</a></li>
 </ul><br/>
 
 <li>3D Simulator</li>
 <ul>
 <li><a href="http://gazebosim.org/tutorials/?tut=ros_comm">Gazebo</a></li>
 </ul><br/>
 
 <li>3D Visualization Tool</li>
 <ul>
  <li><a href="http://wiki.ros.org/rviz">ROS-Visualization (RViz)</a></li>
 </ul><br/>
 
</ul>

## Installation
The installation process will be discussed in this section for informing the reader with some background. <br/><br/>

<i>1. Virtual Machine and Ubuntu Install</i><br/><br/>

<div align="center">
<img src = "PR/Pictures/Virtualbox Setup.png" height = "360px" style="margin:10px 10px"> 
<br/><br/>  
</div>

Since the host operating system (OS) for computers utilised were windows, a linux os was needed to employ ROS. This team planned to use the Kinetic Kame ROS distribution. The first step was to download the Oracle Virtualbox for free and install onto respective computers. The next step was to download and install Ubuntu 16.04 LTS to use in the Virtualbox environment. For more information on setting up ubuntu on Virtual box, please refer to the <a href="https://itsfoss.com/install-linux-in-virtualbox/">step by step tutorial</a>. 
<br/><br/>

<i>2. Kinetic Kame ROS Distro Install</i><br/><br/>

<div align="center">
<img src = "PR/Pictures/kinetic kame.png" height = "360px" style="margin:10px 10px">
<br/><br/>
</div> 

Once Ubuntu 16.04 LTS is successfully configured into the vitual environment, the next step was to install Kintec Kame ROS distribution. For detailed steps on how to download Kinetic Kame ROS distribution on Ubuntu 16.04 LTS, please refer to the <a href="http://wiki.ros.org/kinetic/Installation/Ubuntu">ROS Kinetic installation guide</a>.
<br/><br/>

Once ROS Kinetic is installed, verify that ros is installed by opening a new terminal (<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd> : to open terminal in ubuntu) and typing in the following:<br/>
```
printenv | grep ROS
```
<br/>
If Ros Kinetic is not installed then refer back to the <a href="http://wiki.ros.org/kinetic/Installation/Ubuntu">ROS Kinetic installation guide</a> again or check other online resources related to installing ROS Kinetic such as the <a href="http://wiki.ros.org/">ROS Wiki</a>. If installed properly then proceed to <a href="http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment">configuring the ROS environment</a>.
<br/><br/>

<i>3. Installing Warthog Software</i><br/><br/>

<div align="center">
<img src = "PR/Pictures/warthog_banner.png" height = "360px" style="margin:10px 10px">
<br/><br/>
</div> 

Once the ROS environment is setup, the next step is to install the Warthog through Clearpath Robotic's<a href="https://www.clearpathrobotics.com/assets/guides/kinetic/warthog/WarthogInstallation.html">Warthog software installation guide</a>.
<br/><br/>

<code style="color:red">This is red?</code>


# 🖧 A Network Topology designed using Cisco Packet Tracer Named 'Institution Network Model'

<a href="https://github.com/hritik-dot"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=hritik-dot&style=flat-square" width="125"/></a>
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Network-Simulation-Using-Cisco-Packet-Tracer.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/harismuneer/Network-Simulation-Using-Cisco-Packet-Tracer/fork)
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Network-Simulation-Using-Cisco-Packet-Tracer.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Network-Simulation-Using-Cisco-Packet-Tracer/issues)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)

I designed this **network configuration for the network of college campus**, given some constraints. This problem was presented in our  Computer Networks Lab (CL307) Final. The main role was to **subnet the IP addresses** correctly.

Its an interesting problem demonstrating the concepts of **Classless IP Subnetting** and using **RIPv2 Protocol**. I am sharing this **working solution** so that it might be of help to others looking to learn these concepts with a practical real world example.


## Designed Network
![a](../master/Screenshot of institute network model.PNG)


## Problem Statement
Suppose that you are the CEO of a startup which deals with network configuration for various companies and college campuses. After 100 days of struggle, you have finally received your first assignment to configure the network for college campus which you have studied in such a way that all the PCs in each department of your college must be able to communicate with each other as well as with all the PCs of any other department as well as the canteen and dean office and andministrative block.

As part of the agreement, all departments, canteens and administrative block have asked you to bear the expense of all the switches and routers used to interconnect all the computers in a merged network for three companies and further instructed you that **all the PCs in a single room must be on the same sub network and all the rooms of a single department must be on a different sub-network which will be assigned after sub-netting the assigned *network address* only for the relevant room** (no outside network or the network of other rooms will be accepted) 

You, beign cleverly economical, decide to install old switces (**Generic Switches** in Cisco Packet Tracer) with only Ethernet ports working and routers (**Generic Routers** in Cisco Packet Tracer) to configure the network for college campus in such a way that you use as much less routers and switches as possible. 

You have also bought the folliwng IP network address for the serial communication between different routers which will be connecting different college departments. You plan to form the subnets of the following address in order to cater the serial communication between all the routers: **Routers Serial Communication: 199.210.121.160/28**

## Constraints

You, being very cautious, decide to **simulate the topology on Cisco Packet Tracer** in order to optimally design the network considering the number of devices (switches, routers etc.) used to maximize the profit margins of your company. However, you must simulate the topology strictly following rules and regulations described below:

**1-** Use Straight Through wires, Cross Over cables or Serial DCE wires where necessary and applicable.

**2-** Use Generic Router and Generic PCs for your design

**3-** Use Generic Switches such that you attach  available **Ethernet Interfaces** for a single switch, however, you can attach as many switches considering optimal design.

**4-** You have to assign IPs to the PCs using **Static IP allocation**.

**5-** Although you have to use GUI of the router to configure its interfaces but you must use CLI of the router to configure the **RIPv2 Protocol** for **Classless Subnet Addressing**.

## How to Run
Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) and then simply open the [Institution Networking Model.pkt](../master/main/Institution Networking Model.pkt). The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.

This solution works for version 6.2 or above of Cisco Packet Tracer.

<br>
<hr>
<h1 align="left">Hey there, I'm <a href="https://www.linkedin.com/in/hritik-dot/">Hritik </a><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">


<hr>

<h2 align="left">🌐 Connect</h2>
<p align="left">
  <a href="https://www.linkedin.com/in/hritik-talwatkar-77a251195/"><img title="Follow on LinkedIn" src="https://www.linkedin.com/in/hritik-talwatkar-77a251195?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.facebook.com/hritik.talwatkar/"><img title="Connect on Facebook" src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>
  <a href="https://twitter.com/ezhritik"><img title="Follow on Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/></a>
  <a href="talwatkarh8928@gmail.com"><img title="Email" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/hritik-dot"><img title="Follow on GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.instagram.com/hritiktalwatkar"><img title="Follow on Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
  <a href="https://www.youtube.com/channel/UCN4g5gCSCsrG7Y6L-g6OuHw?sub_confirmation=1"><img title="Subscribe on YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
</p>




## 👨‍💻 Technical Skills & Expertise

- Development of Web Applications
- Development of Machine Learning/Deep Learning models, and deployment 
-  Python Scripting
<hr>


## ❤️ Support / Donations
If you or your company use any of my projects, like what I’m doing or have benefited from my projects in any way then kindly consider backing my efforts.

 
If you face any issue in sending donation then feel free to get in touch with me at talwatkarh8928@gmail.com 



If you liked the repo then kindly support it by giving it a star ⭐ and share in your circles so more people can benefit from the effort.

## Contributions Welcome
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)

If you find any bug in the code or have any improvements in mind then feel free to generate a pull request.


Copyright (c) 2022-present, hritiktalwatkar                                                      

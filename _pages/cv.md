---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Bachelor of Electrical & Electronics Engineering, Ho Chi Minh City University of Technology, Oct 2016 - Oct 2020
  * Honors Program
  * Thesis: Design and implementation of an FPGA-based crypto accelerator for IPsec VPN
  * Location: Ho Chi Minh city, Vietnam

Work experience
======
* August 2022 - August 2025: Communications Testbed Engineer
  * Future Comms R&D Programme - FCCLab - APOS
  * 5G Networks and Open RAN System Research
  * Location: Singapore
  * Duties included:
    * Publication: RAN Intelligent Controller (RIC): From open-source implementation to real-world validation
      - Reproduce NexRAN to see how E2 interface works and network slicing feature
      - Explore srsRAN Project and openairinterface5g with USRP as gNB
      - Implement wrapper function for QCT RAN into E2 agent of flexRIC platform
      - Implement simple workflow for KPM xApp using flexRIC platform
    * Publication: AI-Driven rApps for Reducing Radio Access Network Interference in Real-World 5G Deployment
      - Support for integrating the control scripts for the RUs
    * Develop Energy Saving rApp demonstration at MWC Barcelona 2024
      - Demonstrated dynamic switching of base stations based on predicted user traffic
      - Simulated through VIAVI RAN Scenario Generator
      - Turn on and off the cells based on predicted throughput
    * Develop Interference Management rApp demonstration at RIC forum 2024
      - Experiment with multiple scenarios of indoor-outdoor interference zone
      - Develop rApp to turn off the cell when the interference is detected
    * Develop Traffic Steering xApp in Spring Plugfest 2024 at APOS
      - Develop Traffic Steering xApp inside VMWare's Near Real-time RIC Platform
      - Using RAN Scenario Generator from VIAVI to simulate the UEs
    * Co-develop the course about Radio Intelligent Controller with Asia Open RAN Academy
      - Prepare a hands-on course using srsRAN project as gNB
      - Using flexRIC and light-weight version of OSC RIC
      - Prepare hands-on tutorial to install all components inside an VM
    * Testing engineer at Plugfest Spring and Fall 2024
      - Conduct Security Assurance Specification (SCAS) Test cases for gNB
      - Conduct E2 interface testing
      - Conduct End-to-End test cases for gNB

* Apr. 2021 - Jul. 2022: Software Developer
  * Techedge Ltd
  * Location: Vietnam
  * Duties included:
    * Edge gateway for solar rooftop monitoring system
      - Develop monitoring and control services at the edge gateway and cloud
      - IIoT network management with virtual P2P VPN
    * Multi-robots system development in 3D simulator environment
      - Develop exploration algorithm for UGV
      - Configure UAV navigation stack parameters to work with 3D voxblox map
      - Develop a technique for communicating between a 3D environment (Unity) and a multirobot platform

* Nov. 2020 - Apr. 2021: Software Developer
  * Impact Technical Resources Vietnam Corporation
  * Location: Vietnam
  * Duties included:
    * Classification algorithm for ECG signal
      - Develop algorithms for ECG-based heartbeat classification for arrhythmia detection
      - Develop ECG-based GRU model for abnormal heartbeat symptoms

* Nov. 2019 - Apr. 2020: Software Developer
  * Viettel High Technology Industries Corporation
  * Location: Vietnam
  * Duties included:
    * IPsec VPN service for SOHO router
      - System programming (socket, file, TCP/IP, IPC, multithreading) in C
      - Linux kernel network driver
      - IPsec stack integration into developing SOHO router

* Jun. 2019 - Dec. 2020: Software Developer (Thesis)
  * Location: Vietnam
  * Duties included:
    * SOHO VPN router
      - Linux kernel module for FPGA based cryptographic accelerator
      - Communication between extended FPGA Board and router through PCIe
      - Interaction of the network stack and cryptography in the Linux kernel
      - Improving IPsec VPN speed of development SOHO router using extended FPGA

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors and Awards
======
* Best Demo Paper Award at The 2nd Workshop on Next-generation Open and Programmable Radio Access Networks (NG-OPERA), INFOCOM WKSHPS, 2024
<!-- * Be elected as one of 50 students to join the contest for selecting Vietnam team joining the International Mathematical Olympiad - 2016 -->
<!-- * Second prize in National Excellent Student Contest in Maths, Vietnam, 2016 -->
* Consolation prize in National Excellent Student Contest in Maths, Vietnam, 2015
<!-- * Bronze Medal Southern Olympiad 30/4 in Maths, 2015 -->

Skills
======
* **Tools:** Docker, Git, VM, Kubernetes, ESXi
<!-- * **Linux system programming:** Programming with file, socket, multithread, IPC -->
* **Environment:** Linux, Robot Operating System
* **Programming Languages:** C/C++, Python, Bash script.
<!-- * **Microcontroller programming:** Hands-on experience with ARM Cortex-M4 microcontrollers -->

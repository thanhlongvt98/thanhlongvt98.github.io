---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-section {
  margin-bottom: 2.5em;
}

.cv-section h2 {
  border-bottom: 2px solid var(--global-border-color);
  padding-bottom: 0.5em;
  margin-bottom: 1em;
  margin-top: 1.5em;
  font-size: 1.5em;
  color: var(--global-text-color);
}

.cv-section h2:first-of-type {
  margin-top: 0;
}

.cv-item {
  margin-bottom: 1.5em;
  padding-left: 1em;
}

.cv-item-title {
  font-weight: 600;
  font-size: 1.1em;
  margin-bottom: 0.3em;
  color: var(--global-text-color);
}

.cv-item-meta {
  color: var(--global-text-color-light);
  font-size: 0.9em;
  margin-bottom: 0.5em;
}

.cv-item-details {
  margin-top: 0.5em;
  padding-left: 1.5em;
}

.cv-item-details li {
  margin-bottom: 0.3em;
}

.cv-nested-list {
  margin-top: 0.3em;
  padding-left: 1.5em;
}

.cv-nested-list li {
  margin-bottom: 0.2em;
}
</style>

## Education

<div class="cv-item">
  <div class="cv-item-title">Bachelor of Electrical & Electronics Engineering</div>
  <div class="cv-item-meta">Ho Chi Minh City University of Technology | Oct 2016 - Oct 2020 | Ho Chi Minh city, Vietnam</div>
  <ul class="cv-item-details">
    <li>Honors Program</li>
    <li>Thesis: Design and implementation of an FPGA-based crypto accelerator for IPsec VPN</li>
  </ul>
</div>

## Work Experience

<div class="cv-item">
  <div class="cv-item-title">Communications Testbed Engineer</div>
  <div class="cv-item-meta">Future Comms R&D Programme - FCCLab - APOS | August 2022 - August 2025 | Singapore</div>
  <div class="cv-item-meta"><em>5G Networks and Open RAN System Research</em></div>
  <ul class="cv-item-details">
    <li><strong>Publication:</strong> RAN Intelligent Controller (RIC): From open-source implementation to real-world validation
      <ul class="cv-nested-list">
        <li>Reproduce NexRAN to see how E2 interface works and network slicing feature</li>
        <li>Explore srsRAN Project and openairinterface5g with USRP as gNB</li>
        <li>Implement wrapper function for QCT RAN into E2 agent of flexRIC platform</li>
        <li>Implement simple workflow for KPM xApp using flexRIC platform</li>
      </ul>
    </li>
    <li><strong>Publication:</strong> AI-Driven rApps for Reducing Radio Access Network Interference in Real-World 5G Deployment
      <ul class="cv-nested-list">
        <li>Support for integrating the control scripts for the RUs</li>
      </ul>
    </li>
    <li><strong>Develop Energy Saving rApp demonstration at MWC Barcelona 2024</strong>
      <ul class="cv-nested-list">
        <li>Demonstrated dynamic switching of base stations based on predicted user traffic</li>
        <li>Simulated through VIAVI RAN Scenario Generator</li>
        <li>Turn on and off the cells based on predicted throughput</li>
      </ul>
    </li>
    <li><strong>Develop Interference Management rApp demonstration at RIC forum 2024</strong>
      <ul class="cv-nested-list">
        <li>Experiment with multiple scenarios of indoor-outdoor interference zone</li>
        <li>Develop rApp to turn off the cell when the interference is detected</li>
      </ul>
    </li>
    <li><strong>Develop Traffic Steering xApp in Spring Plugfest 2024 at APOS</strong>
      <ul class="cv-nested-list">
        <li>Develop Traffic Steering xApp inside VMWare's Near Real-time RIC Platform</li>
        <li>Using RAN Scenario Generator from VIAVI to simulate the UEs</li>
      </ul>
    </li>
    <li><strong>Co-develop the course about Radio Intelligent Controller with Asia Open RAN Academy</strong>
      <ul class="cv-nested-list">
        <li>Prepare a hands-on course using srsRAN project as gNB</li>
        <li>Using flexRIC and light-weight version of OSC RIC</li>
        <li>Prepare hands-on tutorial to install all components inside an VM</li>
      </ul>
    </li>
    <li><strong>Testing engineer at Plugfest Spring and Fall 2024</strong>
      <ul class="cv-nested-list">
        <li>Conduct Security Assurance Specification (SCAS) Test cases for gNB</li>
        <li>Conduct E2 interface testing</li>
        <li>Conduct End-to-End test cases for gNB</li>
      </ul>
    </li>
  </ul>
</div>

<div class="cv-item">
  <div class="cv-item-title">Software Developer</div>
  <div class="cv-item-meta">Techedge Ltd | Apr. 2021 - Jul. 2022 | Vietnam</div>
  <ul class="cv-item-details">
    <li><strong>Edge gateway for solar rooftop monitoring system</strong>
      <ul class="cv-nested-list">
        <li>Develop monitoring and control services at the edge gateway and cloud</li>
        <li>IIoT network management with virtual P2P VPN</li>
      </ul>
    </li>
    <li><strong>Multi-robots system development in 3D simulator environment</strong>
      <ul class="cv-nested-list">
        <li>Develop exploration algorithm for UGV</li>
        <li>Configure UAV navigation stack parameters to work with 3D voxblox map</li>
        <li>Develop a technique for communicating between a 3D environment (Unity) and a multirobot platform</li>
      </ul>
    </li>
  </ul>
</div>

<div class="cv-item">
  <div class="cv-item-title">Software Developer</div>
  <div class="cv-item-meta">Impact Technical Resources Vietnam Corporation | Nov. 2020 - Apr. 2021 | Vietnam</div>
  <ul class="cv-item-details">
    <li><strong>Classification algorithm for ECG signal</strong>
      <ul class="cv-nested-list">
        <li>Develop algorithms for ECG-based heartbeat classification for arrhythmia detection</li>
        <li>Develop ECG-based GRU model for abnormal heartbeat symptoms</li>
      </ul>
    </li>
  </ul>
</div>

<div class="cv-item">
  <div class="cv-item-title">Software Developer</div>
  <div class="cv-item-meta">Viettel High Technology Industries Corporation | Nov. 2019 - Apr. 2020 | Vietnam</div>
  <ul class="cv-item-details">
    <li><strong>IPsec VPN service for SOHO router</strong>
      <ul class="cv-nested-list">
        <li>System programming (socket, file, TCP/IP, IPC, multithreading) in C</li>
        <li>Linux kernel network driver</li>
        <li>IPsec stack integration into developing SOHO router</li>
      </ul>
    </li>
  </ul>
</div>

<div class="cv-item">
  <div class="cv-item-title">Software Developer (Thesis)</div>
  <div class="cv-item-meta">Jun. 2019 - Dec. 2020 | Vietnam</div>
  <ul class="cv-item-details">
    <li><strong>SOHO VPN router</strong>
      <ul class="cv-nested-list">
        <li>Linux kernel module for FPGA based cryptographic accelerator</li>
        <li>Communication between extended FPGA Board and router through PCIe</li>
        <li>Interaction of the network stack and cryptography in the Linux kernel</li>
        <li>Improving IPsec VPN speed of development SOHO router using extended FPGA</li>
      </ul>
    </li>
  </ul>
</div>

## Honors and Awards

<div class="cv-item">
  <ul class="cv-item-details" style="list-style-type: disc; padding-left: 2em;">
    <li>Best Demo Paper Award at The 2nd Workshop on Next-generation Open and Programmable Radio Access Networks (NG-OPERA), INFOCOM WKSHPS, 2024</li>
    <li>Consolation prize in National Excellent Student Contest in Maths, Vietnam, 2015</li>
  </ul>
</div>

<!-- ## Skills

<div class="cv-item">
  <ul class="cv-item-details" style="list-style-type: none; padding-left: 0;">
    <li><strong>Tools:</strong> Docker, Git, VM, Kubernetes, ESXi</li>
    <li><strong>Environment:</strong> Linux, Robot Operating System</li>
    <li><strong>Programming Languages:</strong> C/C++, Python, Bash script</li>
  </ul>
</div> -->

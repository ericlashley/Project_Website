---
layout: default
title: Robotic Arm Lab Upgrade
title: Senior Design - University of South Florida Spring 2025
---

<style>
.tab-container {
  margin-top: 20px;
}

.tab-buttons {
  display: flex;
  margin-bottom: 10px;
  flex-wrap: wrap;
}

.tab-buttons button {
  padding: 10px 20px;
  cursor: pointer;
  border: 1px solid #ccc;
  border-bottom: none;
  background-color: #f1f1f1;
  margin-right: 5px;
  font-weight: bold;
}

.tab-buttons button.active {
  background-color: #fff;
  border-bottom: 1px solid #fff;
}

.tab-content {
  border: 1px solid #ccc;
  padding: 15px;
  display: none;
  background-color: #fff;
}

.tab-content.active {
  display: block;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const buttons = document.querySelectorAll(".tab-buttons button");
  const contents = document.querySelectorAll(".tab-content");

  buttons.forEach((button, index) => {
    button.addEventListener("click", () => {
      buttons.forEach(btn => btn.classList.remove("active"));
      contents.forEach(content => content.classList.remove("active"));

      button.classList.add("active");
      contents[index].classList.add("active");
    });
  });

  // Activate first tab by default
  buttons[0].classList.add("active");
  contents[0].classList.add("active");
});
</script>

# Robotic Arm Lab Upgrade

Welcome to our Senior Design project website! This page contains our documentation, progress, and all deliverables from Design 1 and Design 2 courses.

---

## Motivation
<!-- Insert your project motivation here -->
Our goal is to upgrade the robotic arm lab experience for future students by introducing new capabilities and streamlined interfaces.

## Problem Formulation
<!-- Insert your problem statement here -->
The current robotic lab setup is outdated and lacks ROS 2 support. We aim to redesign the architecture and integrate a more modern system.

## Parts
Here are the main components used in this project:
- Niryo One Robotic Arm
- Jetson Nano / Raspberry Pi
- Custom Power Supply Unit
- ROS 2 Humble / Foxy Packages
- 3D Printed Mounts and Fixtures

## Progress
- Design 1: Hardware benchmarking
- Design 2: ROS 2 integration began


## Videos
- [Demo 1 - Basic Motor Test](#)


---

## Project Deliverables

<div class="tab-container">
  <div class="tab-buttons">
    <button>Design 1</button>
    <button>Design 2</button>
  </div>

  <div class="tab-content">
    <h3>Design 1 Assignments</h3>
    <ul>
      <li><a href="#">Proposal Report</a></li>
      <li><a href="#">System Block Diagram</a></li>
      <li><a href="#">Bill of Materials</a></li>
      <li><a href="#">Initial Simulation Results</a></li>
      <li><a href="#">Final Presentation</a></li>
      <!-- Add more Design 1 items as needed -->
    </ul>
  </div>

  <div class="tab-content">
    <h3>Design 2 Assignments</h3>
    <ul>
      <li><a href="#">Project Timeline</a></li>
      <li><a href="#">Test Plans</a></li>
      <li><a href="#">Controller Implementation</a></li>
      <li><a href="#">System Testing Videos</a></li>
      <li><a href="#">Final Documentation</a></li>
      <!-- Add more Design 2 items as you complete them -->
    </ul>
  </div>
</div>

---

## Notes
All Design 1 assignments are archived here for reference. Design 2 documents and progress will be added immediately after each submission deadline.

---

© 2025 Senior Design Team – Robotic Arm Lab Upgrade


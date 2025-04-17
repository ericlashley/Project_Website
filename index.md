---
layout: default
title: Robotic Arm Lab Upgrade
---

<style>
.tab-container {
  margin-top: 20px;
}

.tab-buttons {
  display: flex;
  margin-bottom: 10px;
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

## Project Overview

<!-- Add general info, motivation, etc. -->

---

<div class="tab-container">
  <div class="tab-buttons">
    <button>Design 1</button>
    <button>Design 2</button>
  </div>

  <div class="tab-content">
    <h3>Design 1 Assignments</h3>
    <ul>
      <li><a href="#">Assignment 1</a></li>
      <li><a href="#">Assignment 2</a></li>
      <!-- More Design 1 assignments -->
    </ul>
  </div>

  <div class="tab-content">
    <h3>Design 2 Assignments</h3>
    <ul>
      <li><a href="#">Assignment 1</a></li>
      <li><a href="#">Assignment 2</a></li>
      <!-- More Design 2 assignments -->
    </ul>
  </div>
</div>


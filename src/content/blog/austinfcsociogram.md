---
layout: ../../layouts/LayoutBlogPost.astro
title: "Austin FC"
description: "Austin FC"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/austinfcsoc.jpg"
---

# Sociogram Project


I improved upon [<a href="http://rhydlewis.eu/sociogram/" style="color: lightblue;" target="_blank">this</a>](http://rhydlewis.eu/sociogram/) existing sociogram visualization tool created in VBA by Dr. Rhydian Lewis at The University of Cardiff.

The original tool was created for an educational setting. I tailored and optimized it for a professional soccer club.

The tool allows relationships among and between players and coaches to automatically be visualized in a user-friendly manner.
<br><br>
**How it works:**
<ol>
  <li style="color: white;">1. The Excel-based tool fetches raw data from an online survey that asks coaches and players several questions (names changed for privacy reasons).</li>
  <img src="/sociogram1.png"><br>
  <li style="color: white;">2. The data is cleansed and converted into numerical form. The user selects a question to visualize.</li>
  <img src="/sociogram2.png"><br>
  <li style="color: white;">3. A matrix showing which player who chose who is created based on the inputted data.</li>
  <img src="/sociogram3.png"><br>
  <li style="color: white;">4. A sociogram is then drawn, with nodes placed and arrows drawn based on the number of players and the players' responses.</li>
  <img src="/sociogram4.png">
</ol>
<br><br>

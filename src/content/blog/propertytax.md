---
layout: ../../layouts/LayoutBlogPost.astro
title: "Property Tax Fighter"
description: "Property Tax Fighter"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/propertytax.jpg"
---

# Data Visualization & Machine Learning

<style>
.video-container {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 */
  height: 0;
}
.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.pdf {
  position: relative;
  width: 100%; /* 100% of the page width */
  padding-top: 177.78%; /* (16/9) * 100 = 177.78% to maintain 9:16 aspect ratio */
  overflow: hidden;
}

.pdf embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

</style>

**Background:** Homeowners often face financial and logistical challenges when disputing their property tax appraisals, which can sometimes be set at the highest permissible values by appraisal districts. The current process requires time, specialized knowledge, and resources that many homeowners lack. 

**Aim:** The goal of this project is to create a website that utilizes local home pricing data and machine learning models to empower homeowners with data-driven insights, helping them contest their property taxes more effectively and affordably.

**Action:** Built a Flask app using machine learning to help homeowners protest property taxes with comparables, estimates, and interactive visualizations.
<br><br>
**Video Summary:**

<div class="video-container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/luQ4e8LgvPM?si=zXEmLYrzBZlgSrQK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br><br>
**Full Project Report:**
<div class="pdf">
<embed src="/propertytaxreport.pdf" width="100%" height="100%" 
 type="application/pdf">
</div>

<br><br>
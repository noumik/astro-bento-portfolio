---
layout: ../../layouts/LayoutBlogPost.astro
title: "Analyzing Voters"
description: "Analyzing Voters"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/voters.jpg"
---

# Machine Learning

<style>
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

[<a href="https://github.com/noumik/Analyzing-Voters" style="color: lightblue;" target="_blank">GitHub Link</a>](https://github.com/noumik/Analyzing-Voters)

This project extensively utilized Python and various libraries (Pandas, Sklearn, Matplotlib) in order to predict how Americans will vote.

A large dataset was obtained from the Cooperative Congressional Election Study. We cleansed the data and only retained the features that were relevant to our analysis.

We created a neural network and final model which predicted, with 66.67% accuracy, how a voter would cast their ballot.

Our report is below. The code is on GitHub, with our methodology clearly presented.
<br><br>
**Full Project Report:**
<div class="pdf">
<embed src="/analyzingvoters.pdf" width="100%" height="100%" 
 type="application/pdf">
</div>

<br><br>
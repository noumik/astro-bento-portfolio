---
layout: ../../layouts/LayoutBlogPost.astro
title: "Predicting ETF Returns"
description: "Predicting ETF Returns"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/etfs.jpg"
---

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
<br>
This analysis looked at whether certain characteristics of an ETF can help predict its 5 year return.

The dataset we used for our analysis includes over 2,000 ETFs and was scraped from Yahoo Finance.
<br><br>
**Video Summary:**

<div class="video-container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<br><br>
**Full Project Report:**
<div class="pdf">
<embed src="/etfreturns.pdf" width="100%" height="100%" 
 type="application/pdf">
</div>

<br><br>

[<a href="https://github.com/noumik/Predicting-ETF-Returns" style="color: lightblue;" target="_blank">See the R code on GitHub</a>](https://github.com/noumik/Predicting-ETF-Returns)

<br><br>
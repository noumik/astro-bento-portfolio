---
layout: ../../layouts/LayoutBlogPost.astro
title: "2018 Michigan State Legislative Election Analysis"
description: "2018 Michigan State Legislative Election Analysis"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/mielection.png"
---


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
<br>
I was tasked with performing an analysis on the 2018 Michigan State Legislative Elections. I analyzed results from the State House, State Senate, and Gubernatorial races. My analysis mainly focused on how political parties performed in each chamber in comparison to the number of votes they received. I also analyzed the election turnout and its relation to the results.
<br><br>
PivotTables were utilized extensively. Excel was used for creating visualizations to present in the analysis.
<br><br>

**Full Project Report:**
<div class="pdf">
<embed src="/mielection.pdf" width="100%" height="100%" 
 type="application/pdf">
</div>

<br><br>
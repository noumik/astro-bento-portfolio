---
layout: ../../layouts/LayoutBlogPost.astro
title: "Employee Attrition Predictor"
description: "Employee Attrition Predictor"
pubDate: 2023-01-21
category: "intro"
headerImage: "/src/lib/employeeattrition.png"
---

# Machine Learning Prediction

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

**Background:** In this study, we investigated whether machine learning could be used to predict employee attrition and support organizational retention efforts. Using a synthetic employee dataset, we prepared the data through encoding, scaling, and dimensionality reduction techniques, then trained and evaluated several classification models, including Logistic Regression, KNN, Random Forest, AdaBoost, Neural Networks, and SVMs.
<br><br>
Our results showed that models trained on the full feature set consistently outperformed those using PCA-reduced data. AdaBoost achieved the highest accuracy, while Random Forest produced the strongest overall F1 score. Although predictive performance was moderate, the findings demonstrate that machine learning can provide valuable insights into attrition risk and help organizations improve workforce planning, retention strategies, and future data-driven decision making.
<br><br>
**Full Project Report:**
<div class="pdf">
<embed src="/employeeattrition.pdf" width="100%" height="100%" 
 type="application/pdf">
</div>
<br><br>

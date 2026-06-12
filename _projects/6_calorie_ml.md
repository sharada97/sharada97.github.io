---
layout: page
title: Multimodal Calorie Estimation
description: Estimating meal calories from photos, continuous glucose data, and demographics using XGBoost and neural networks.
img: assets/img/6.jpg
importance: 6
category: machine learning
---

A multimodal model that estimates the calories of meals from sensing data, photographs, gut-health signals, and demographics, trained on data from 40+ participants over up to 10 days.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/calorie.jpg" title="Per-ingredient calorie breakdown of a meal" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- Combined XGBoost and neural networks; achieved 34% error on unseen data.
- Placed in the top 10% of the Texas A&M Machine Learning course (grade: A).
- Code: [Food_Calorie_prediction_ML](https://github.com/sharada97/Food_Calorie_prediction_ML)

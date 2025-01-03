---
layout: post
title: a post with images
date: 2025-01-03 11:41:00
description: a post with image
tags: formatting images
categories: sample-posts
thumbnail: assets/img/9.jpg
---

Some delicious meals.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cookies.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Puff Pastry Breakfast .jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    It makes me feel so hungry.
</div>

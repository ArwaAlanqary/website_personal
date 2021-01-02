---
title: Time series analysis using matrix estimation 
summary: An algorithm for forecasting and imputation of time series data. 
tags:
- Time Series
date: "2020-11-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<p>
<div style="text-align: justify"> 
The problem of noisy and missing data is almost inevitable in any dataset. Accurate imputation algorithms are essential to recover missing values before further analysis is performed as most algorithms are promised complete data. This project focuses on imputing univariate time series data that suffer form missing vales in the form long blocks of consecutive missing entries. 
</div>
</p>

<p>
<div style="text-align: justify"> 
A recent approach towards time series imputation utilizes matrix completion algorithms to recover missing values. This approach converts the time series into a matrix then apply well-established matrix completion algorithms. In this project we proposed an extension to this approach to increase the imputation accuracy in the presence of diverse blocks of consecutive missing values (check the figure below). 
</div>
</p>


![algorithm diag](alg_diag.png)



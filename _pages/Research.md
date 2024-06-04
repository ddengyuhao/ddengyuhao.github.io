---
layout: archive
title: "Publication"
permalink: /research/
author_profile: true
description: Publications in reversed chronological order.
nav_order: 1
---

<!-- # Main Publications -->

{% include base_path %}

{% assign index = 1 %}
{% for post in site.publications reversed %}
  {% include archive-single.html index=index %}
  {% assign index = index | plus: 1 %}
{% endfor %}



<br>
<br>

# Other Publications


{% include base_path %}

{% assign index = 1 %}
{% for post in site.otherpapers reversed %}
  {% include archive-single.html index=index %}
  {% assign index = index | plus: 1 %}
{% endfor %}


<!-- ## Working Papers -->
<!-- - [Oct 2022] "Copula Graphic Estimation of Survival Function with Dependent Censoring and its Application to an Analysis of Pancreatic Cancer Clinical Trial," with [Jung Hyun Jo](https://scholar.google.co.kr/citations?user=8fpu8j0AAAAJ&hl=ko), [Inkyung Jung](https://ir.ymlib.yonsei.ac.kr/researcher-profile?ep=3502&type=1), [Hyungsik Roger Moon](https://dornsife.usc.edu/hyungsik-roger-moon/), [Geert Ridder](https://dornsife.usc.edu/cf/econ/econ_faculty_display.cfm?Person_ID=1003639) and [Si Young Song](https://orcid.org/0000-0002-1417-4314). Resubmitted at *Statistical Methods in Medical Research*. \[[R package](https://github.com/zhan-gao/CopulaGraphic)\] 
- [Apr 2022] "Identification and Estimation of Categorical Random Coefficient Models," with [M. Hashem Pesaran](http://pesaran.com/). Revise and Resubmit at *Empirical Economics*. \[[*Cambridge Working Papers in Economics, CWPE2228*](https://www.econ.cam.ac.uk/research/cwpe-abstracts?cwpe=2228)\]\[[CESifo Working Paper No. 9714](https://www.cesifo.org/en/publikationen/2022/working-paper/identification-and-estimation-categorical-random-coefficient)\]\[[R package](https://github.com/zhan-gao/ccrm)\]  -->

<!-- ## Publications -->

<!-- - [2024] "[On LASSO for Predictive Regression](https://www.sciencedirect.com/science/article/pii/S030440762100049X)," with [Ji Hyung Lee](https://sites.google.com/site/jihyung412/home) and [Zhentao Shi](https://zhentaoshi.github.io/). *Journal of Econometrics*,  *229*(2), 322-349. [[supplement](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/LSG_supp.pdf)\][[code](https://github.com/zhan-gao/Alasso_Predictive_Regression)\]\[[arXiv: 1810.03140](https://arxiv.org/abs/1810.03140)\][[slides](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/alasso_slides_online.pdf)\]
  
- [2024] "[MisDetect: Iterative Mislabel Detection using Early Loss](https://link.springer.com/article/10.1007/s10614-020-09995-z)," with [Zhentao Shi](https://zhentaoshi.github.io/). *Computational Economics*, 58, 1127-1135. [[supplement](https://github.com/zhan-gao/convex_prog_in_econometrics/blob/master/main_supp_lyx.pdf)\][[code](https://github.com/zhan-gao/convex_prog_in_econometrics)]\[[arXiv: 1806.10423](https://arxiv.org/abs/1806.10423)\] -->


<!-- - [2024] "[IDE: A System for Iterative Mislabel Detection](https://www.sciencedirect.com/science/article/pii/S030440762100049X)," with [Ji Hyung Lee](https://sites.google.com/site/jihyung412/home) and [Zhentao Shi](https://zhentaoshi.github.io/). *Journal of Econometrics*,  *229*(2), 322-349. [[supplement](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/LSG_supp.pdf)\][[code](https://github.com/zhan-gao/Alasso_Predictive_Regression)\]\[[arXiv: 1810.03140](https://arxiv.org/abs/1810.03140)\][[slides](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/alasso_slides_online.pdf)\]

- [2024] "[LakeBench: A Benchmark for Discovering Joinable and Unionable Tables in Data Lakes](https://www.sciencedirect.com/science/article/pii/S030440762100049X)," with [Ji Hyung Lee](https://sites.google.com/site/jihyung412/home) and [Zhentao Shi](https://zhentaoshi.github.io/). *Journal of Econometrics*,  *229*(2), 322-349. [[supplement](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/LSG_supp.pdf)\][[code](https://github.com/zhan-gao/Alasso_Predictive_Regression)\]\[[arXiv: 1810.03140](https://arxiv.org/abs/1810.03140)\][[slides](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/alasso_slides_online.pdf)\]

- [2024] "[Outlier Summarization via Human Interpretable Rules](https://www.sciencedirect.com/science/article/pii/S030440762100049X)," with [Ji Hyung Lee](https://sites.google.com/site/jihyung412/home) and [Zhentao Shi](https://zhentaoshi.github.io/). *Journal of Econometrics*,  *229*(2), 322-349. [[supplement](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/LSG_supp.pdf)\][[code](https://github.com/zhan-gao/Alasso_Predictive_Regression)\]\[[arXiv: 1810.03140](https://arxiv.org/abs/1810.03140)\][[slides](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/alasso_slides_online.pdf)\]
  
- [2024] "[MisDetect: Iterative Mislabel Detection using Early Loss](https://www.sciencedirect.com/science/article/pii/S030440762100049X)," with [Ji Hyung Lee](https://sites.google.com/site/jihyung412/home) and [Zhentao Shi](https://zhentaoshi.github.io/). *Journal of Econometrics*,  *229*(2), 322-349. [[supplement](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/LSG_supp.pdf)\][[code](https://github.com/zhan-gao/Alasso_Predictive_Regression)\]\[[arXiv: 1810.03140](https://arxiv.org/abs/1810.03140)\][[slides](https://github.com/zhan-gao/Alasso_Predictive_Regression/blob/master/alasso_slides_online.pdf)\] -->



---
layout: post
title: 'Three New Papers'
date: 2026-07-31
author: Kaitlyn Murgatroyd
categories:
- blog
img: 
thumb:
---

There are three recently published papers to highlight.

The first paper is [Technical Note: Using Benchmark Ensembles to Reduce the Impact of Streamflow Variability on Model Performance Metrics](https://doi.org/10.1029/2026WR043517) by Paul, Wouter, Cyril, Nico, Martyn, and Al.

Hydrological models are commonly evaluated by seeing how well the simulated streamflow matches observed streamflow. One of the most common methods for doing this compares the performance of the model to the performance obtained by using the average observed flow and thus answers the question “is my model better than using the average flow”. The problem is that the average flow is much easier to beat in some rivers (such as snowmelt dominated rivers where flow is very high in the spring and low in the winter) than in others (such as dry regions where flow is usually very low except for rare high flow events). Comparing a model to the average flow in different regions makes it hard to tell if your model gets a good score because the model is good, or because the average flow was too easy to beat.

This paper presents a more comprehensive approach for evaluating simulated streamflow by using many different comparisons instead of only relying on the average flow. The authors compare model performance to 20 simple ways of estimating streamflow across North America and found that no single method is the best test of model performance everywhere. Instead, you should test your model against many different alternative estimates of streamflow and select the most difficult test to beat. This helps make sure that you get a good score because your model is good, and not because you are comparing it to something that is too easy to beat. This can help modellers better understand in which locations their models are performing well, and in which locations improvements can be made. The research presented in this paper was funded by CIROH (grant number: NA22NWS4320003)


<p align="center">
 <img src="{{ '/assets/img/Paul_figure.jpg' | relative_url }}" 
alt="Spatial distribution of benchmark efficiency (BME) skill scores across the CAMELS-SPAT basins for benchmarks in different categories. Panel (f) shows the lowest BME score of the ensemble at each catchment. Red dots denote BME values below 0. Histograms are included with all negative values being included in the red bin, the gray histograms in (b–f) correspond to the Mean Flow (Nash-Sutcliffe Efficiency) (from Coderre et al. 2026)." 
style="max-width:700px; width:100%;"> 
</p> 
<p align="center"><em>Spatial distribution of benchmark efficiency (BME) skill scores across the CAMELS-SPAT basins for benchmarks in different categories. Panel (f) shows the lowest BME score of the ensemble at each catchment. Red dots denote BME values below 0. Histograms are included with all negative values being included in the red bin, the gray histograms in (b–f) correspond to the Mean Flow (Nash-Sutcliffe Efficiency) (from Coderre et al. 2026).</em></p>

The second paper to highlight is [Lake monitoring and research efforts in Alberta, Canada: an assessment of 15-years of published literature focusing on assessing research collaborations and partnerships](https://doi.org/10.1080/07011784.2026.2705521) by Kaitlyn, David, Brad (Alberta Lake Management Society), Fred, and Kerry.

The review presents an analysis of recent lake research and monitoring in Alberta. The authors asked the following questions: who is doing lake research in Alberta? who are they doing it with? where are they doing it? and what specific endpoints are they looking at? The results show a bias toward academic-led research with collaborations primarily occurring with governments and non-government organizations. The paper identifies and discusses a significant gap in Indigenous representation in academic research articles, both as authors and collaborators. Oil and gas extraction and refinement drove research in the Athabasca watershed (the most commonly researched region), with water quality endpoints as the most common endpoints.  

This review emphasizes the need for enhanced collaboration between academia, government, and communities. Specific recommendations include standardized data repositories with comprehensive metadata, improved Indigenous representation on editorial boards and in community-based monitoring initiatives, and more Indigenous data sovereignty training and awareness in academic and governmental research training and review processes. The authors call for transformative approaches to integrate diverse knowledge systems to bridge gaps in research equity and environmental stewardship and improve lake management.

<p align="center">
 <img src="{{ '/assets/img/Kaitlyn_figure.jpg' | relative_url }}" 
alt="Number of manuscripts regarding Alberta lakes focused on each river basin region. Light blue indicates few studies, and dark blue indicates many studies. Data sources: ESRI Basemap and Government of Alberta Base Watersheds layers (from Murgatroyd et al. 2026). " 
style="max-width:600px; width:100%;"> 
</p> 
<p align="center"><em>Number of manuscripts regarding Alberta lakes focused on each river basin region. Light blue indicates few studies, and dark blue indicates many studies. Data sources: ESRI Basemap and Government of Alberta Base Watersheds layers (from Murgatroyd et al. 2026).</em></p>

The third paper is [Improving the Numerical Solution of the Energy Equation in Land Models](https://doi.org/10.1029/2025MS005353) by Ashley, Raymond (USask), and Martyn.

This study aims to improve the accuracy of land models by improving how they numerically solve the energy equation. The authors show that the methods most commonly used at present can lead to large errors, especially in cold regions, causing inaccurate predictions of soil temperature and water content. The authors test five different ways to solve the energy equation, including new methods that use advanced techniques to control errors, over North America. The authors recommend two new approaches, where there is a trade-off between strictly conserving energy and reducing overall errors in the simulation variables. Improving these calculations will help researchers build better models for understanding land processes.

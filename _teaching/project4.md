---
title: "MCM/ICM 2018"
collection: teaching
type: "Contest"
permalink: /projects/project4
venue: "Wuhan University"
date: 2018-02-01
location: "Wuhan China"
---
In MCM/ICM 2018, we were awarded as Meritorious Winner. In this contest, we chose the problem D, organizing a charging network for electric vehicles. During our preperation, we proposed a top-down model for network design optimization. The following is the summary of our paper.




Optimizing network of charging stations: A top-down approach
======

Keywords: Electric Vehicle; Station Planning; Top-down Approach; Network 
------

We construct a top-down model on planning the charging station for electric vehicles with the target of developing an all-electrical vehicle traffic system gradually.

The problem contains three main points: the position, optimal amount, and the sequence of building them. We separate it into three levels: Country-level: determine the maximum number of charging stations; Network-level: determine the sequence of edge (road) selection; City-level: determine the accurate position of each charging station within city scale. On country-level, we develop Charging Stations Amount Estimation Sub-model (CSAE), which is under ideal assumptions to estimate the number of destination charging stations needed in each city and average density of supercharging stations needed on each road if everyone switched to all-electric. As for network-level, depending partly on the Connectivity-Freedom Degree (CFD) to evaluate the benefit to graph of an edge, Top-level Network Sequence Selection, Sub-model (TNSS) can effectively and efficiently find out the sequence of roads along which we build charging stations. Finally, on City-level, City-scale Charging Station Planning Sub-model (CCSP) is designed to plan accurate positions for every charging stations, given the maximum number of charging stations within a city. CCSP takes population density, traffic flow within a district and the capacity of a charging station into account. In this paper, models are introduced in a top-down order: CSAE, TNSS and CCSP. 

To evaluate the efficacy of every model, we perform experiments on both synthetic and real data. Results show that our model both meets the requirement of this problem and accurately generates an optimal solution. Additionally, the model we proposed is compatible with further extension and has a high execution efficiency.


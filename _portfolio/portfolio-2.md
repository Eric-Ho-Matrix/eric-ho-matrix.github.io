---
title: "Robots Localization"
excerpt: "Localization <br/><img src='/images/NeRF.png'>"
collection: portfolio
---

<p align = "justify"> 
Robot localization has long been a challenging task. While traditional Computer Vision has succeeded in SLAM(Simultaneous Localization and Mapping), some rapidly evolving technology bring new perpectives to this region. Neural radiance fields (NeRFs) (https://doi.org/10.48550/arXiv.2003.08934) put forward a new method for 3D reconstruction. NeRF take point position as input and output color and density of a given point. This new feature exactly matches the need of Robotics community. Based on NeRF, some reversal usage of NeRF is put forward for localization (https://doi.org/10.48550/arXiv.2012.05877). Since NeRF is a continuous model, gradient-based method is well-siuted to apply. Some researches have been conducted for NeRF-based robot Navigation in simulation (https://doi.org/10.48550/arXiv.2110.00168). And loc-NeRF is used for real time localizatoin (1Hz) (https://doi.org/10.48550/arXiv.2209.09050). 

The main limitation of NeRF-based method is its speed. SOTA solution for localization cannot meet requirement for aerial robots since latter require loclization speed as fast as 100 Hz. Our research aims at using NaRF (B. Steder, R. B. Rusu, K. Konolige and W. Burgard, "Point feature extraction on 3D range scans taking into account object boundaries," 2011 IEEE International Conference on Robotics and Automation, Shanghai, China, 2011, pp. 2601-2608) combined with one of SOTA VIO-based localization algorithm VINS_FUSIOIN (https://doi.org/10.48550/arXiv.1708.03852) perform multi-robots localization. The robots planning is conducted by RLSS(https://doi.org/10.1007/s10514-023-10104-w)
</p>
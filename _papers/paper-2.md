---
title: "Geometry Distance Constrained Robust Registration Framework of Featureless Point Clouds"
excerpt: "Ziwei Wang"
collection: papers
---
Authors: Ziwei Wang, **Xiaoyu Lin**, Wei Chen, Zeyuan Yang, Xiaojian Zhang, Sijie Yan<sup>\*</sup>, Han Ding.
Submitted to _IEEE Transactions on Industrial Informatics_ (R&R).

Abstract
======
  In large-scale metrology (LSM), the transformation of the tracker base frame (TBF) is a predominant method to enlarge the field of view (FOV) of the tracking sensor for full-field 3D measurements. Nevertheless, such a process will introduce cumulative errors and significantly diminish the global point cloud alignment accuracy. To address this problem, we propose a novel tracker pose optimization method for TBF transformation. A pose graph optimization (PGO) model based on spatial distance constraints is implemented to improve the tracker pose accuracy. We also adopt a robust coefficient and a damping factor to simplify the experimental process and stabilize the convergence results. Simulations and experiments on high-speed train surfaces are conducted to validate our method’s accuracy and effectiveness. The
results indicate that our optimization method outperforms two existing methods in spatial positioning accuracy and point cloud alignment accuracy, which showcases its practical applicability and superiority in manufacturing scenarios.

Highlights
======
* A tracker pose optimization method is proposed for a robotic measuring system based on photogrammetry tracking.
* A pose graph optimization method based on spatial distance constraints is introduced to improve the optimization accuracy.
* A robust coefficient and a damping factor are adopted to simplify the experimental process and stabilize the convergence results.
* Simulations and experiments on high-speed train surfaces are conducted to verify the method’s effectiveness and to demonstrate the superiority of the proposed method over the two existing methods.

System Overview
======
<div align=center>
 <img src="/images/papers/setup.png" width="600" />
</div>
<div align=center>
 <img src="/images/papers/exp.png" width="600" />
</div>

Achievements
======
* Achieved the 3D measurement of high-speed train surfaces under multiple tracker base frames (TBFs), and demonstrated that the proposed method could serve as an accurate, flexible, and applicable framework for large-scale metrology scenarios.
* Reduced the spatial positioning error of the tracker after TBF transformation by more than 50%, compared with the existing best-fit method and the sphere-based method.
<div align=center>
<img src="/images/papers/cloudc.png" width="500" />
</div>
<div align=center>
<img src="/images/papers/ess_compare_avg.png" width="600" />
</div>
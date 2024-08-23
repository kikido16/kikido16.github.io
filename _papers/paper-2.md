---
title: "Geometry Distance Constrained Robust Registration Framework of Featureless Point Clouds"
excerpt: "Ziwei Wang"
collection: papers
---
Authors: Ziwei Wang, **Xiaoyu Lin**, Wei Chen, Zeyuan Yang, Xiaojian Zhang, Sijie Yan<sup>\*</sup>, Han Ding.

Submitted to _IEEE Transactions on Industrial Informatics_ (R&R).

Abstract
======
Registration of featureless point clouds (FPC) with outliers, noisy data, and partial overlaps is intractable in 3D reconstruction. We derive that in some Iterative Closest Point (ICP) variants, such as point-to-plane and symmetric metrics, the upper bounds of their error landscapes are nearly zero in FPC, resulting in slow convergence or local minima. To address the above challenges, we introduce a constrained registration framework, which integrates geometry distance constraints (GDC) and weighted enhanced distance (WED) metric to achieve a robust registration in FPC. Specifically, WED combines point-to-point and pointto-plane metrics, resulting in a steeper error landscape; GDCs constrain the transformation matrix into a feasible subset to escape local minima. Moreover, we introduce a dynamic slack of constraint algorithm (DSC) to improve the stability of the linear perturbation in the constrained registration problem. Simulations and experiments are conducted on some typical featureless objects, including a turbine blade, a cylinder-ruled surface, an outlet guide vane, and an engine rotor, to verify the effectiveness and efficiency of the presented registration framework.

Highlights
======
* A tracker pose optimization method is proposed for a robotic measuring system based on photogrammetry tracking.
* A pose graph optimization method based on spatial distance constraints is introduced to improve the optimization accuracy.
* A robust coefficient and a damping factor are adopted to simplify the experimental process and stabilize the convergence results.
* Simulations and experiments on high-speed train surfaces are conducted to verify the method’s effectiveness and to demonstrate the superiority of the proposed method over the two existing methods.

System Overview
======
<div align=center>
 <img src="/images/papers/realScene.png" width="500" />
</div>

Achievements
======
* Achieved the 3D measurement of high-speed train surfaces under multiple tracker base frames (TBFs), and demonstrated that the proposed method could serve as an accurate, flexible, and applicable framework for large-scale metrology scenarios.
* Reduced the spatial positioning error of the tracker after TBF transformation by more than 50%, compared with the existing best-fit method and the sphere-based method.
<div align=center>
<img src="/images/papers/results.png" width="600" />
</div>


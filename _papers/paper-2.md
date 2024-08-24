---
title: "Geometry Distance Constrained Robust Registration Framework of Featureless Point Clouds"
excerpt: "***Aiming to achieve more precise and robust point cloud registration between partially-overlapped featureless point clouds.*** <br/><img src='/images/papers/realScene.png' width='500'>"
collection: papers
---
Authors: Ziwei Wang, **Xiaoyu Lin**, Wei Chen, Zeyuan Yang, Xiaojian Zhang, Sijie Yan<sup>\*</sup>, Han Ding.

Submitted to _IEEE Transactions on Industrial Informatics_ (R&R).

Abstract
======
Registration of featureless point clouds (FPC) with outliers, noisy data, and partial overlaps is intractable in 3D reconstruction. We derive that in some Iterative Closest Point (ICP) variants, such as point-to-plane and symmetric metrics, the upper bounds of their error landscapes are nearly zero in FPC, resulting in slow convergence or local minima. To address the above challenges, we introduce a constrained registration framework, which integrates geometry distance constraints (GDC) and weighted enhanced distance (WED) metric to achieve a robust registration in FPC. Specifically, WED combines point-to-point and pointto-plane metrics, resulting in a steeper error landscape; GDCs constrain the transformation matrix into a feasible subset to escape local minima. Moreover, we introduce a dynamic slack of constraint algorithm (DSC) to improve the stability of the linear perturbation in the constrained registration problem. Simulations and experiments are conducted on some typical featureless objects, including a turbine blade, a cylinder-ruled surface, an outlet guide vane, and an engine rotor, to verify the effectiveness and efficiency of the presented registration framework.

Highlights & Achievements
======
* Derived the upper bound of error landscape symmetric and point-to-plane metrics.
* Proposed a registration framework that incorporated geometry distance constraints (GDC) and weighted enhanced distance (WED). 
* Introduced a dynamic slack of constraint (DSC) algorithm to stabilize the perturbation solution in registration.
* Achieved more accurate point cloud registration for FRC, compared with the existing registration methods for FRC.
<div align=center>
<img src="/images/papers/results.png" width="600" />
</div>


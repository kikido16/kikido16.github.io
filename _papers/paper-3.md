---
title: "High Accuracy and Robust Robotic Inspection by Constrained Pose Graph Optimization"
excerpt: "Short description of portfolio item number 2"
collection: papers
---
Authors:  Ziwei Wang, Yifan Yang, Sijie Yan<sup>\*</sup>, **Xiaoyu Lin**, Xiaojian Zhang, Han Ding. 

Submitted to _IEEE Transactions on Industrial Electronics_ (Major revision).

Abstract
======
Pose graph optimization (PGO) methods are extensively used in robotic inspection (RI) to estimate accurate 3D scanner poses. However, some inaccurate
pairwise relative measurements decrease the accuracy of PGO. To achieve a robust and accurate RI, we propose
a new framework called robust constrained pose graph optimization (RCPGO). Specifically, we introduce some additional landmarks to construct a constrained pose graph (CPG) and improve the accuracy of PGO by CPG’s spatial geometry consistency. Furthermore, the symmetric (SYMM) distance function is introduced to construct the objective function of RCPGO, which has a higher D-optimality design metric upper bound and contributes to the robustness and accuracy of RCPGO. To solve the SYMM-RCPGO problem in $SE_{3}^{N}$, we linearize the problem into sequential quadratic programming (SQP) and solve the perturbation of $SE_{3}^{N}$ by the interior-point method. Moreover, a dynamic constraints boundaries algorithm is proposed to prevent inaccurate linearization caused by large perturbation. To assess the effectiveness of SYMM-RCPGO, we conducted comparative evaluations with traditional PGO in both simulated cylinder surfaces and real high-speed train scenes. The results validate the robustness and accuracy of SYMM-RCPGO and find that a few constraints can significantly reduce pose error. Our source code and data are available at https://github.com/Timbersaw-wangzw/SYMM_RCPGO.git.

Highlights
======
* A tracker pose optimization method is proposed for a robotic measuring system based on photogrammetry tracking.
* A pose graph optimization method based on spatial distance constraints is introduced to improve the optimization accuracy.
* A robust coefficient and a damping factor are adopted to simplify the experimental process and stabilize the convergence results.
* Simulations and experiments on high-speed train surfaces are conducted to verify the method’s effectiveness and to demonstrate the superiority of the proposed method over the two existing methods.

System Overview
======
<div align=center>
 <img src="/images/papers/draw.png" width="600" />
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

---
title: "High Accuracy and Robust Robotic Inspection by Constrained Pose Graph Optimization"
excerpt: "***Aiming to obtain more precise tracker poses during the tracker pose base frame transformation process.***<br/><img src='/images/papers/system.png' width='600'>"
collection: papers
---
Authors:  Ziwei Wang, Yifan Yang, Sijie Yan<sup>\*</sup>, **Xiaoyu Lin**, Xiaojian Zhang, Han Ding. 

Submitted to _IEEE Transactions on Industrial Electronics_ (Major revision).

Abstract
======
Pose graph optimization (PGO) methods are extensively used in robotic inspection (RI) to estimate accurate 3D scanner poses. However, some inaccurate
pairwise relative measurements decrease the accuracy of PGO. To achieve a robust and accurate RI, we propose a new framework called robust constrained pose graph optimization (RCPGO). Specifically, we introduce some additional landmarks to construct a constrained pose graph (CPG) and improve the accuracy of PGO by CPG’s spatial geometry consistency. Furthermore, the symmetric (SYMM) distance function is introduced to construct the objective function of RCPGO, which has a higher D-optimality design metric upper bound and contributes to the robustness and accuracy of RCPGO. To solve the SYMM-RCPGO problem in SE<sub>3</sub><sup>N</sup>, we linearize the problem into sequential quadratic programming (SQP) and solve the perturbation of SE<sub>3</sub><sup>N</sup> by the interior-point method. Moreover, a dynamic constraints boundaries algorithm is proposed to prevent inaccurate linearization caused by large perturbation. To assess the effectiveness of SYMM-RCPGO, we conducted comparative evaluations with traditional PGO in both simulated cylinder surfaces and real high-speed train scenes. The results validate the robustness and accuracy of SYMM-RCPGO and find that a few constraints can significantly reduce pose error. Our source code and data are available at [https://github.com/Timbersaw-wangzw/SYMM_RCPGO.git](https://github.com/Timbersaw-wangzw/SYMM_RCPGO.git).

Highlights & Achievements
======
* Proposed a symmetric distance function to provide a higher D-optimality design metric upper bound than the traditional PGO.
* Introduced a dynamic constraints boundaries algorithm to avoid inaccurate linearization caused by large perturbations to enhance stability during the optimization procedure.
* Proposed a symmetric robust constrained pose graph optimization (SYMM-RCPGO) framework that achieves more robust and accurate pose estimation than traditional PGO methods.

<div align=center>
 <img src="/images/papers/draw.png" width="600" />
</div>



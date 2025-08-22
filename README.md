# MIT-SDP-Robotics-Seminar

At the Massachusetts Institute of Technology, we run the SDP Robotics Seminar, which features a mix of reading groups, presentations, and talks by authors of recent or impactful papers. This repository contains a list of papers we have reviewed or authors we've hosted.

If you have any suggestions, want to chat, or are interested in presenting, feel free to reach out!

<!--  
## YYYY-MM-DD:

### Title
**Author(s)**:
<details span>
<summary><b>Abstract</b></summary>
Text
</details>

  [📄 Paper]() |  [🌐 Project Page]() | [💻 Code]() -->


## 2025-09-05:

### Regularization Methods for SDP Relaxations in Large-Scale Polynomial Optimization
**Author(s)**: Jiawang Nie, Li Wang
<details span>
<summary><b>Abstract</b></summary>
We study how to solve semidefinite programming (SDP) relaxations for large-scale
polynomial optimization. When interior-point methods are used, typically only small or moderately
large problems could be solved. This paper studies regularization methods for solving polynomial
optimization problems. We describe these methods for semidefinite optimization with block struc-
tures and then apply them to solve large-scale polynomial optimization problems. The performance
is tested on various numerical examples. With regularization methods, significantly bigger problems
could be solved on a regular computer, which is almost impossible with interior point methods.
</details>

  [📄 Paper](https://epubs.siam.org/doi/pdf/10.1137/110825844)

## 2025-08-22

### A Survey of Recent Scalability Improvements for Semidefinite Programming with Applications in Machine Learning, Control, and Robotics
**Author(s)**: Anirudha Majumdar, Georgina Hall, and Amir Ali Ahmadi
<details span>
<summary><b>Abstract</b></summary>
Historically, scalability has been a major challenge to the successful application of semidefinite programming in fields such as machine learning, control, and robotics. In this paper, we survey recent approaches for addressing this challenge including (i) approaches for exploiting structure (e.g., sparsity and symmetry) in a problem, (ii) approaches that produce low-rank approximate solutions to semidefinite programs, (iii) more scalable algorithms that rely on augmented Lagrangian techniques and the alternating direction method of multipliers, and (iv) approaches that trade off scalability with conservatism (e.g., by approximating semidefinite programs with linear and second-order cone programs). For each class of approaches we provide a high-level exposition, an entry-point to the corresponding literature, and examples drawn from machine learning, control, or robotics. We also present a list of software packages that implement many of the techniques discussed in the paper. Our hope is that this paper will serve as a gateway to the rich and exciting literature on scalable semidefinite programming for both theorists and practitioners.
</details>

  [📄 Paper](https://arxiv.org/pdf/1908.05209)

## 2025-08-08

### SDP Synthesis of Distributionally Robust Backward Reachable Trees for Probabilistic Planning
**Author(s)**: Naman Aggarwal, Jonathan P. How
<details span>
<summary><b>Abstract</b></summary>
The paper presents Maximal Ellipsoid Backward Reachable Trees MAXELLIPSOID BRT, which is a multi-query algorithm for planning of dynamic systems under stochastic motion uncertainty and constraints on the control input. In contrast to existing probabilistic planning methods that grow a roadmap of distributions, our proposed method introduces a framework to construct a roadmap of ambiguity sets of distributions such that each edge in our proposed roadmap provides a feasible control sequence for a family of distributions at once leading to efficient multi-query planning. Specifically, we construct a backward reachable tree of maximal size ambiguity sets and the corresponding distributionally robust edge controllers. Experiments show that the computation of these sets of distributions, in a backwards fashion from the goal, leads to efficient planning at a fraction of the size of the roadmap required for state-of-the-art methods. The computation of these maximal ambiguity sets and edges is carried out via a convex semidefinite relaxation to a novel nonlinear program. We also formally prove a theorem on maximum coverage for a technique proposed in our prior work on probabilistic planning [2].
</details>

  [📄 Paper](https://ieeexplore.ieee.org/document/11029077)

## 2025-07-25

### Estimation Contracts for Outlier-Robust Geometric Perception
**Author(s)**: Luca Carlone
<details span>
<summary><b>Abstract</b></summary>
Outlier-robust estimation is a fundamental problem and has been extensively investigated by statisticians and practitioners. The last few years have seen a convergence across research fields towards "algorithmic robust statistics", which focuses on developing tractable outlier-robust techniques for high-dimensional estimation problems. Despite this convergence, research efforts across fields have been mostly disconnected from one another. This monograph bridges recent work on certifiable outlier-robust estimation for geometric perception in robotics and computer vision with parallel work in robust statistics. In particular, we adapt and extend recent results on robust linear regression (applicable to the low-outlier regime with << 50% outliers) and list-decodable regression (applicable to the high-outlier regime with >> 50% outliers) to the setup commonly found in robotics and vision, where (i) variables (e.g., rotations, poses) belong to a non-convex domain, (ii) measurements are vector-valued, and (iii) the number of outliers is not known a priori. The emphasis here is on performance guarantees: rather than proposing radically new algorithms, we provide conditions on the input measurements under which modern estimation algorithms (possibly after small modifications) are guaranteed to recover an estimate close to the ground truth in the presence of outliers. These conditions are what we call an "estimation contract". The monograph also provides numerical experiments to shed light on the applicability of the theoretical results and to showcase the potential of list-decodable regression algorithms in geometric perception. Besides the proposed extensions of existing results, we believe the main contributions of this monograph are (i) to unify parallel research lines by pointing out commonalities and differences, (ii) to introduce advanced material (e.g., sum-of-squares proofs) in an accessible and self-contained presentation for the practitioner, and (iii) to point out a few immediate opportunities and open questions in outlier-robust geometric perception.
</details>

  [📄 Paper](https://arxiv.org/pdf/2208.10521)

## Credits
- Co-organizers of this seminar group: Andrew Fishberg and Lorenzo Shaikewitz
- Thanks to all the presenters and participants!
- This webpage is adapted from the [MIT-PALS](https://github.com/annika-thomas/MIT-PALS) seminar website.

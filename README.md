# GNN-based-PDE-solvers

Contributed by Xueqin Chen, AidroLab, TU Delft

## [Content](#content)
<table>
<tr><td colspan="2"><a href="#models">Models</a></td></tr>
<tr>
    <td>&ensp;<a href="#other">1. Other</a></td>
    <td>&ensp;<a href="#multi-resolution">2. Multi-resolution</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#dl-numerical">3. DL-Numerical </a></td>
    <td>&ensp;<a href="#mesh-reduced">4. Mesh-reduced </a></td>
</tr>
<tr>
    <td>&ensp;<a href="#computation-cost">5. Computation cost </a></td>
    <td>&ensp;<a href="#inverse-problem">6. Inverse problem </a></td>
</tr>
<tr>
    <td>&ensp;<a href="#particle-based">7. Particle-based </a></td>
</tr>
</table>

## [Models](#content) 
### [Other](#content)
1. **Learning mesh-based simulation with graph networks.** ICLR, 2021. [paper](https://openreview.net/forum?id=roNqYL0_XP)

   *Tobias Pfaff, Meire Fortunato, Alvaro Sanchez-Gonzalez, and Peter Battaglia.*
1. **Message passing neural PDE solvers.** ICLR, 2022. [paper](https://openreview.net/forum?id=vSix3HPYKSU)

   *Johannes Brandstetter, Daniel E. Worrall, and Max Welling.*
1. **Learning the solution operator of boundary value problems using graph neural networks.** ICML, 2022. [paper](https://arxiv.org/abs/2206.14092)

   *Winfried Lötzsch, Simon Ohler, and Johannes S. Otterbach.*
   
1. **Physics-constrained unsupervised learning of partial differential equations using meshes.** arXiv, 2022. [paper](https://arxiv.org/abs/2203.16628)

   *Mike Y. Michelis and Robert K. Katzschmann.*

2. **Neural PDE solvers for irregular domains.** arXiv, 2022. [paper](https://arxiv.org/abs/2211.03241)

   *Biswajit Khara, Ethan Herron, Zhanhong Jiang, Aditya Balu, Chih-Hsuan Yang, Kumar Saurabh, Anushrut Jignasu, Soumik Sarkar, Chinmay Hegde, Adarsh Krishnamurthy, and Baskar Ganapathysubramanian.*

1. **Learning time-dependent PDE solver using message passing graph neural networks.** arXiv, 2022. [paper](https://openreview.net/forum?id=oaKw-GmBZZ)

   *Pourya Pilva and Ahmad Zareei.*
   
1. **Differentiable physics-informed graph networks.** arXiv, 2019. [paper](https://arxiv.org/abs/1902.02950)

   *Sungyong Seo and Yan Liu.*

1. **MG-GNN: Multigrid graph neural networks for learning multilevel domain decomposition methods.** arXiv, 2023. [paper](https://arxiv.org/abs/2301.11378)

   *Ali Taghibakhshi, Nicolas Nytko, Tareq Uz Zaman, Scott MacLachlan, Luke Olson, and Matthew West.*


1. **An implicit GNN solver for Poisson-like problems.** arXiv, 2023. [paper](https://arxiv.org/abs/2302.10891)

   *Matthieu Nastorg, Michele-Alessandro Bucci, Thibault Faney, Jean-Marc Gratien, Guillaume Charpiat, and Marc Schoenauer.*

1. **GNN-based physics solver for time-independent PDEs.** arXiv, 2023. [paper](https://arxiv.org/abs/2303.15681v1)

   *Rini Jasmine Gladstone, Helia Rahmani, Vishvas Suryakumar, Hadi Meidani, Marta D'Elia, and Ahmad Zareei.*

### [Multi-resolution](#content)
1. **Multi-scale physical representations for approximating PDE solutions with graph neural operators.** ICLR, 2022. [paper](https://arxiv.org/abs/2206.14687)

   *Léon Migus, Yuan Yin, Jocelyn Ahmed Mazari, and Patrick Gallinari.*
 
1. **Bi-stride multi-scale graph neural network for mesh-based physical simulation.** arXiv, 2022. [paper](https://arxiv.org/abs/2210.02573)

   *Yadi Cao, Menglei Chai, Minchen Li, and Chenfanfu Jiang.*

1. **Multi-scale message passing neural PDE solvers.** arXiv, 2023. [paper](https://arxiv.org/abs/2302.03580)

   *Léonard Equer, T. Konstantin Rusch, and Siddhartha Mishra.*


### [DL-Numerical](#content)
1. **Combining differentiable PDE solvers and graph neural networks for fluid flow prediction.** ICML, 2022. [paper](https://dl.acm.org/doi/10.5555/3524938.3525162)

   *Filipe de Avila Belbute-Peres, Thomas D. Economon, and J. Zico Kolter.*

### [Mesh-reduced](#content)
1. **Predicting physics in mesh-reduced space with temporal attention.** ICLR, 2022. [paper](https://openreview.net/forum?id=XctLdNfCmP)

   *Xu Han, Han Gao, Tobias Pfaff, Jianxun Wang, and Liping Liu.*


### [Computation cost](#content)
1. **Learning large-scale subsurface simulations with a hybrid graph network simulator.** KDD, 2022. [paper](https://arxiv.org/abs/2206.07680)

   *Tailin Wu, Qinchen Wang, Yinan Zhang, Rex Ying, Kaidi Cao, Rok Sosič, Ridwan Jalali, Hassan Hamam, Marko Maucec, and Jure Leskovec.*

### [Inverse problem](#content)
1. **Learning to solve PDE-constrained inverse problems with graph networks.** ICML, 2022. [paper](https://openreview.net/pdf?id=cLR6FCyMY5k)

   *Zhao Qingqing, David B. Lindell, and Gordon Wetzstein.*
   
   
### [Particle-based](#content)
1. **Learning to simulate complex physics with graph networks.** ICML, 2020. [paper](https://dl.acm.org/doi/10.5555/3524938.3525722)

   *Alvaro Sanchez-Gonzalez, Jonathan Godwin, Tobias Pfaff, Rex Ying, Jure Leskovec, and Peter W. Battaglia.*
1. **E(3) equivariant graph neural networks for particle-based fluid mechanics.** ICLR, 2023. [paper](https://arxiv.org/abs/2304.00150v1)

   *Artur P. Toshev, Gianluca Galletti, Johannes Brandstetter, Stefan Adami, and Nikolaus A. Adams.*
   

1. **Physics-Embedded Neural Networks: Graph Neural PDE Solvers with Mixed Boundary Conditions.** NIPS, 2022. [paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/93476ae409ae3246e22a9d4b931f84ed-Paper-Conference.pdf)

   *Masanobu Horie and Naoto Mitsume.*

1. **Physics-aware difference graph networks for sparsely-observed dynamics.** ICLR, 2020. [paper](https://openreview.net/forum?id=r1gelyrtwH)

   *Sungyong Seo, Chuizheng Meng, and Yan Liu.*


1. **Learning continuous-time PDEs from sparse data with graph neural networks.** ICLR, 2021. [paper](https://openreview.net/pdf?id=aUX5Plaq7Oy)

   *Valerii Iakovlev, Markus Heinonen, and Harri Lähdesmäki.*



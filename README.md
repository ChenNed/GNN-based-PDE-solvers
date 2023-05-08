# GNN-based-PDE-solvers

Contributed by Xueqin Chen, AidroLab, TU Delft

## [Content](#content)
<table>
<tr><td colspan="2"><a href="#models">Models</a></td></tr>
<tr>
    <td colspan="2">&ensp;<a href="#input-features">1. Input features</a></td>
</tr>

<tr>
    <td rowspan="3">&ensp;<a href="#multi-scale">2. Multi-scale</a></td>
    <td>&ensp;<a href="#multi-temporal-scale">2.1 Multi-temporal-scale</a></td>
  </tr>
  <tr>
    <td>&ensp;<a href="#multi-spatial-scale">2.2 Multi-spatial-scale</a></td>
  </tr>
  <tr>
    <td>&ensp;<a href="#hybrid">2.3 Hybrid </a></td>
  </tr>

<tr>
    <td colspan="2">&ensp;<a href="#dl-numerical">3. DL + Numerical </a></td>
</tr>

<tr>
    <td colspan="2">&ensp;<a href="#symmetry">4. Symmetry </a></td>
</tr>

<tr>
    <td colspan="2">&ensp;<a href="#particle-based">7. Particle-based </a></td>
</tr>

<tr>
    <td colspan="2">&ensp;<a href="#inverse-problem">6. Inverse problem </a></td>
</tr>
</table>

## [Models](#content) 
### [Input features](#content)
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

### [Multi-scale](#content)
The multi-cale means different time and space discretizations.

### [Multi-temporal-scale](#content)
1. **Learning continuous-time PDEs from sparse data with graph neural networks.** ICLR, 2021. [paper](https://openreview.net/pdf?id=aUX5Plaq7Oy) [code](https://github.com/yakovlev31/graphpdes_experiments)

   *Valerii Iakovlev, Markus Heinonen, and Harri Lähdesmäki.*
   
   
### [Multi-spatial-scale](#content)
1. **Multi-resolution Graph Neural Networks for PDE Approximation.** ICANN, 2021. [paper](https://link.springer.com/chapter/10.1007/978-3-030-86365-4_13)

   *Wenzhuo Liu, Mouadh Yagoubi and Marc Schoenauer.* 

1. **Multi-Fidelity Transfer Learning for accurate database PDE approximation.** NeurIPS Workshop Machine Learning and the Physical Sciences, 2022. [paper](https://ml4physicalsciences.github.io/2022/files/NeurIPS_ML4PS_2022_117.pdf)

   *Wenzhuo Liu, Mouadh Yagoubi, David Danan and Marc Schoenauer.* 

1. **AMGNET: multi-scale graph neural networks for flow field prediction.** Connection Science, 2022. [paper](https://www.tandfonline.com/doi/full/10.1080/09540091.2022.2131737) [code](https://github.com/baoshiaijhin/amgnet)

   *Zhishuang Yang, Yidao Dong, Xiaogang Deng and Laiping Zhang.*
   
1. **Towards Fast Simulation of Environmental Fluid Mechanics with Multi-Scale Graph Neural Networks.** ICLR Workshop on AI for Earth and Space Science, 2022. [paper](https://arxiv.org/abs/2205.02637) 

   *Mario Lino, Stathi Fotiadis, Anil A. Bharath and Chris Cantwell.*

1. **REMuS-GNN: A Rotation-Equivariant Model for Simulating Continuum Dynamics.** ICLR Workshop on Geometrical and Topological Representation Learning, 2022. [paper](https://arxiv.org/pdf/2205.07852.pdf)

   *Mario Lino, Stati Fotiadis, Anil A. Bharath and Chris Cantwell.*

1. **Multi-scale rotation-equivariant graph neural networks for unsteady Eulerian fluid dynamics.** Physics of Fluids, 2022. [paper](https://pubs.aip.org/aip/pof/article/34/8/087110/2847850/Multi-scale-rotation-equivariant-graph-neural)

   *Mario Lino, Stati Fotiadis, Anil A. Bharath and Chris Cantwell*
   
1. **Bi-stride multi-scale graph neural network for mesh-based physical simulation.** arXiv, 2022. [paper](https://arxiv.org/abs/2210.02573) [code](https://github.com/Eydcao/BSMS-GNN)

   *Yadi Cao, Menglei Chai, Minchen Li, and Chenfanfu Jiang.*

1. **MultiScale MeshGraphNets.** ICML 2nd AI for Science Workshop, 2022. [paper](https://openreview.net/pdf?id=G3TRIsmMhhf)

   *Meire Fortunato, Tobias Pfaff, Peter Wirnsberger, Alexander Pritzel and Peter Battaglia.*
   
1. **Multiscale Graph Neural Network Autoencoders for Interpretable Scientific Machine Learning.** arXiv, 2023. [paper](https://arxiv.org/abs/2302.06186)

   *Shivam Barwey, Varun Shankar, Venkatasubramanian Viswanathan, Romit Maulik.*

1. **Practical implications of equivariant and invariant graph neural networks for fluid flow modeling.** ICLR Workshop on Physics for Machine Learning, 2023. [paper](https://openreview.net/forum?id=3Y6XRCIUT5)

   *Varun J Shankar, Shivam Barwey, Romit Maulik and Venkatasubraman Viswanathan.*
   
### [Hybrid](#content)
1. **Multi-scale message passing neural PDE solvers.** arXiv, 2023. [paper](https://arxiv.org/abs/2302.03580)

   *Léonard Equer, T. Konstantin Rusch, and Siddhartha Mishra.*



1. ****
   

   




### [DL-Numerical](#content)
1. **Combining differentiable PDE solvers and graph neural networks for fluid flow prediction.** ICML, 2022. [paper](https://dl.acm.org/doi/10.5555/3524938.3525162)

   *Filipe de Avila Belbute-Peres, Thomas D. Economon, and J. Zico Kolter.*
   
   
### [Symmetry](#content)

1. **REMuS-GNN: A Rotation-Equivariant Model for Simulating Continuum Dynamics.** ICLR Workshop on Geometrical and Topological Representation Learning, 2022. [paper](https://arxiv.org/pdf/2205.07852.pdf)

   *Mario Lino, Stati Fotiadis, Anil A. Bharath and Chris Cantwell.*
   
1. **Multi-scale rotation-equivariant graph neural networks for unsteady Eulerian fluid dynamics.** Physics of Fluids, 2022. [paper](https://pubs.aip.org/aip/pof/article/34/8/087110/2847850/Multi-scale-rotation-equivariant-graph-neural)

   *Mario Lino, Stati Fotiadis, Anil A. Bharath and Chris Cantwell*

1. **Practical implications of equivariant and invariant graph neural networks for fluid flow modeling.** ICLR Workshop on Physics for Machine Learning, 2023. [paper](https://openreview.net/forum?id=3Y6XRCIUT5)

   *Varun J Shankar, Shivam Barwey, Romit Maulik and Venkatasubraman Viswanathan.*
   
 
### [Particle-based](#content)
1. **Learning to simulate complex physics with graph networks.** ICML, 2020. [paper](https://dl.acm.org/doi/10.5555/3524938.3525722)

   *Alvaro Sanchez-Gonzalez, Jonathan Godwin, Tobias Pfaff, Rex Ying, Jure Leskovec, and Peter W. Battaglia.*
1. **E(3) equivariant graph neural networks for particle-based fluid mechanics.** ICLR, 2023. [paper](https://arxiv.org/abs/2304.00150v1)

   *Artur P. Toshev, Gianluca Galletti, Johannes Brandstetter, Stefan Adami, and Nikolaus A. Adams.*
   

1. **Physics-Embedded Neural Networks: Graph Neural PDE Solvers with Mixed Boundary Conditions.** NIPS, 2022. [paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/93476ae409ae3246e22a9d4b931f84ed-Paper-Conference.pdf)

   *Masanobu Horie and Naoto Mitsume.*

1. **Physics-aware difference graph networks for sparsely-observed dynamics.** ICLR, 2020. [paper](https://openreview.net/forum?id=r1gelyrtwH)

   *Sungyong Seo, Chuizheng Meng, and Yan Liu.*




### [Inverse problem](#content)
1. **Learning to solve PDE-constrained inverse problems with graph networks.** ICML, 2022. [paper](https://openreview.net/pdf?id=cLR6FCyMY5k)

   *Zhao Qingqing, David B. Lindell, and Gordon Wetzstein.*
   
   





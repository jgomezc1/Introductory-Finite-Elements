# Introduction to the Finite Element Method

![Displacement field in a wrench.](./notebooks/img/wrench.png)

## Introduction

This repository contains teaching resources for an introductory course on Finite Element Analysis. The course in its present form is intended for last year undergraduate students enrolled in the **Mechanical Engineering** and **Civil Engineering** programs at Universidad EAFIT and for first-semester graduate students enrolled in the M.Sc. and Ph.D. programs in the Applied Mechanics track. The course emphasizes on the solution, through finite element algorithms, of the theory of elasticity boundary value problem. It combines theoretical aspects and computational implementations in Python. The material for this introductory course has been typically covered in an 18-weeks semester with 2 hours long weekly meetings. The course is divided into three parts. It starts by covering standard numerical methods such as interpolation theory and numerical quadratures which are numerical tools required in the formulation of finite element algorithms. The course continues with a review of the problem of the theory of elasticity, and particularly its formulation in the form of a boundary value problem stated in terms of the Principle of Virtual Work. The third and final part uses the covered numerical techniques to generate a finite element representation of the virtual work principle

## Flipped class approach

The course has been designed to be imparted in a [flipped classroom environment](https://en.wikipedia.org/wiki/Flipped_classroom) where most of the theoretical contents are covered by the student through independent study complemented with brief homework assignments. On the other hand, the 2-hour class sessions are dedicated to the solution of hands-on computational and theoretical problems under the instructor guidance. For the development of the methodological approach of inverted class the following resources are available in this repository:

* **Lecture notes:** A collection of the theoretical material covered in several textbooks combined with independent developments by the Applied Mechanics Group and organized to facilitate independent study.

* **Notebooks:** A series of Jupyter Notebooks summarizing the theoretical discussion (treated in more detail in the lecture notes) combined with computer implementations in Python. The notebooks contain brief activities intended for self-learning and several, more demanding in-class activities to be developed under the instructor's guidance.

* **SolidsPy:** A Python-based finite element code for the stress analysis of arbitrary two-dimensional domains. The code, which has been developed as part of this course by the Applied Mechanics Group, is structured to be used as a stand-alone application or through the combination of independent modules. The modules used in the different notebooks follow the same structure of those in the code. The code is available in the [Applied Mechanics' repository](https://github.com/AppliedMechanics-EAFIT/SolidsPy).

## Contents

The course contents are those described by the following set of notebooks. **NB-0** covers the basics of Notebooks and provides examples of basic programming skills in Python. **NB-1** through **NB-5** presents standard interpolation and numerical integration techniques but within the context of the finite element method. In particular, **NB-4** applies an initial definition of a finite element to a problem of visualization of functions over two-dimensional domains. The formulation of the finite element method to the elasticity problem is defined in **NB-8** and following.

List of lessons/notebooks:

* [00a: Introductory Notebook](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/00a_introductory.ipynb)

* [00b: A simple finite element code](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/00b_springs.ipynb)

* [01: One-dimensional Lagrange interpolation-Principles](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/01_lagrange_1d_principles.ipynb)

* [02: One-dimensional Lagrange interpolation-Nonlocal scheme](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/02_lagrange_1d_nonlocal.ipynb)

* [03: Two-dimensional Lagrange interpolation](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/03_lagrange_2d.ipynb)

* [04: Application. Visualization of a solution in a complete domain](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/04_lagrange_full.ipynb)

* [05: Numerical integration in the Finite Element Method](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/05_integration.ipynb)

* [06: Computation of the stiffness matrix](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/06_stiffness_matriz.ipynb)

* [07: The linearized theory of elasticity](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/07_elasticity.ipynb)

* [08: Finite element formulation of the elasticity BVP](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/08_fem_bvp_formulation.ipynb)

* [09: Assembly of the FEM equlibrium equations](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/09_assembly.ipynb)

* [10: Solution and post-processing](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/10_solution_and_postprocess.ipynb)

* [11: Convergence analysis of the results](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/11_convergence.ipynb)

* [12: Finite element analysis with SolidsPy](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/12_solidspy.ipynb)

* [13: Truss elements](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/13_truss_elements.ipynb)

* [14: Frame elements](https://nbviewer.jupyter.org/github/jgomezc1/Introductory-Finite-Elements/blob/master/notebooks/14_frame_elements.ipynb)

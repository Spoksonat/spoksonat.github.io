---
title: General Relativity Equation Generator (GREG)
date: 2025-11-15 19:30:00 +/-TTTT
categories: [Software Development, Relativity]
tags: [GREG, General Relativity]     # TAG names should always be lowercase
author: manuel                    # for single entry
description: MRI image analysis tools used by the Physikalisch-Technische Bundesanstalt (PTB)- div. 8.14
toc: True
math: true
---

## About the Project

Python program and LaTeX document to generate a PDF file (called *Cantidades_relativistas.pdf*) containing the relevant quantities of General Relativity for a given metric (the metric tensor, Christoffel symbols, Ricci tensor, Einstein tensor, stress–energy tensor for a perfect fluid, Einstein field equations, the determinant of the metric tensor, Gaussian curvature, geodesic equations, and the Lagrangian). In this implementation, \( c = 1 \).

The program can be executed for three predefined metrics, as well as a manually entered one. The predefined metrics are: Minkowski, Schwarzschild and FLRW (Friedmann–Lemaître–Robertson–Walker).  
The manual mode allows assigning a name to the metric, selecting the coordinates (Spherical, Cylindrical or Cartesian), and entering each component of the metric tensor. A recommended metric to test the manual mode is the Rindler metric in cartesian coordinates:

$$
\begin{align}
  g_{00} = -x^2, \, g_{11}=g_{22}=g_{33}=1, \, g_{\mu \nu}= 0 \, (\mu \neq \nu).
  \label{eq:Rindler}
\end{align}
$$

The manual mode allows the use of six symbolic constants `c_1, c_2, c_3, c_4, c_5, c_6` and eight functions `f_1, f_2, f_3, f_4, f_5, f_6, f_7, f_8`, which can be used when entering each component of the metric tensor. The eight functions may depend on any variable, so the variable dependence must be specified in the console. For example, if the 00 component of the metric tensor should be a function of the variable *theta* in spherical coordinates, then the console input should be:  
`Enter g00: f_1(theta)`.

*Note: The instructions are currently available only in Spanish in the repository.*


You can check the repository here: [GREG GitHub Repo](https://github.com/Spoksonat/Relatividad).
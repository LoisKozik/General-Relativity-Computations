# General-Relativity-Computation
 A Python library for General Relativity Computations

# Overview
This repository contains a script that can perform multiples python symbolic tensor calculation like the Christoffel symbols, the Riemann tensor, the Ricci tensor and the Ricci Scalar. See the exemples on how to use the python library.

# Requirements
This project requires the following Python packages:
- Numpy
- Sympy
- Matplolib
- Plotly
- IPython

# Exemples
### Project 1 : Derivation of the Friedmann Equations
This script derive the Friedmann equations using the General Relativity library from the FLRW metric.

The FLRW metric is given by :

$${\displaystyle {\rm {d}}s^{2}=c^{2}{\rm {d}}t^{2}-a(t)^{2}\left({\frac {{\rm {d}}r^{2}}{1-kr^{2}}}+r^{2}   ({\rm {d}}\theta ^{2}+\sin ^{2}\theta \;{\rm {d}}\phi ^{2})    \right   )}$$

### Project 2 : Schwarszchild Metric
This script verifies that the Schwarzschild metric is a valid solution to the Einstein field equation.

The Schwarszchild Metric is given by :

$$\mathrm {d} s^{2}=-\left(1-{\frac {2GM}{c^{2}r}}\right)c^{2}\mathrm {d} t^{2}+{\frac {\mathrm {d} r^{2}}{1-{\frac {2GM}{c^{2}r}}}}+r^{2}\left(\mathrm {d} \theta ^{2}+\sin ^{2}\theta \,\mathrm {d} \varphi ^{2}\right)$$

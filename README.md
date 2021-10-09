# Image curves reconstruction by means of robust features

Research project supported by FAPESP during October 2020 - September 2021.

**Developer:** André Luís Mendes Fakhoury

**Coordinator:** João do Espirito Santo Batista Neto

The main goal of this research project is to extract robust features in $\mathbb{R}^2$ to reconstruct curves obtained from images. It aims to analyse image preprocessing algorithms, contour extraction of objects, analysis of important points from curves and the respective reconstruction of the original curve.

## Materials and Methods

The development steps of the project can be seen in the following diagram:

![Diagrama](latex\siicusp\resumos\imagens\diagram.png)

The preprocessing aims to eliminate noise on the contour, allowing the extraction of a curvature that better fits it. The identification of important points is done calculating the discrete curvature of the contour. The curve reconstruction is based on a method describe by Sorkine (2006) using a few points (called anchor) and connectivity information, by a discretization of the Laplace-Beltrami operator. The validation is done by comparing the reconstructed curve and the original curve, using the Euclidian distance.

## This repository

There is a *python .ipynb notebook* containing part of the code developed. There is also a *latex* folder containing some reports and presentations (mostly in Portuguese). The *img* directory contains some images extracted from ImageCLEF 2011 database.
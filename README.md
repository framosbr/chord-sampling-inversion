# Chord Sampling and Inversion Methods

Implementation of methods described in: "A Note on Exact Inversion Formulas for Recovering Diameter Distributions of Spherical Particles from Chord-Length Measurements" by J. Koiller, F. Ramos, and S. Zohren.

## Overview

This repository provides implementations of exact mathematical formulas to reconstruct particle size distributions from chord-length measurements. The methods apply to both 2D (silhouette/FBRM) and 3D (intrusive probe) measurement geometries.

## Examples

### 2D Analysis (FBRM-like measurements)

![2D Normal and Mixed Normals](figures/combined/figure1_2D_normal_mixed.png)
*Comparison of radius and chord distributions for 2D circular sections. Top row: Truncated Normal distribution (μ=5.0, σ=1.0). Bottom row: Mixed Normal distribution.*

### 3D Analysis (Intrusive probe measurements)

![3D Lognormal and Gamma](figures/combined/figure4_3D_lognormal_gamma.png)
*Comparison of radius and chord distributions for 3D spherical sections. Top row: Lognormal distribution. Bottom row: Gamma distribution.*

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/chord-sampling-inversion.git
cd chord-sampling-inversion

# Install dependencies
pip install -r requirements.txt

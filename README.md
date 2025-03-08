# Chord Sampling and Inversion Methods

Implementation of methods described in: "A Note on Exact Inversion Formulas for Recovering Diameter Distributions of Spherical Particles from Chord-Length Measurements" by J. Koiller, F. Ramos, and S. Zohren.

## Examples

### 2D Analysis (FBRM-like measurements)

![2D Normal and Mixed Normals](figures/figure1_2D_normal_mixed.png)
*Comparison of radius and chord distributions for 2D circular sections*

![2D Lognormal and Gamma](figures/figure2_2D_lognormal_gamma.png)
*Comparison of lognormal and gamma distributions in 2D*

### 3D Analysis (Intrusive probe measurements)

![3D Normal and Mixed Normals](figures/figure3_3D_normal_mixed.png)
*Comparison of radius and chord distributions for 3D spherical sections*

![3D Lognormal and Gamma](figures/figure4_3D_lognormal_gamma.png)
*Comparison of lognormal and gamma distributions in 3D*

## Usage

This repository contains a Jupyter notebook implementing exact inversion formulas for chord measurements. To use:

1. Clone this repository
2. Install the required dependencies: `numpy`, `scipy`, `matplotlib`
3. Open and run the notebook: `jupyter notebook chord_sampling.ipynb`

## Citation

If you use this code in your research, please cite our paper:

```bibtex
@article{koiller2023exact,
  title={A Note on Exact Inversion Formulas for Recovering Diameter Distributions of Spherical Particles from Chord-Length Measurements},
  author={Koiller, J. and Ramos, F. and Zohren, S.},
  journal={},
  year={2023}
}

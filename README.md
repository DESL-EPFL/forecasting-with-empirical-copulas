# Forecasting with Empirical Copulas

This repository contains the code supporting the paper *Probabilistic Load Forecasting of Distribution Power Systems based on Empirical Copulas*.

## Contents

- **`model/`**: Core implementation of the method
- **`optimized_bandwidths/`**: Results from bandwidth optimization
- **`example.ipynb`**: Example code

### Usage

1. **Data Preparation**:
Place your datasets in the parent directory and adjust the function **load_data** accordingly. Note: data used in the study can be found in [1].

2. **Producing Forecasts**:
   Execute the Jupyter notebooks in the `notebooks/` directory to produce forecasts.

3. **Custom Experiments**:
   Modify the functions in the `model/` directory to produce custom results.

## Citation

If you use this code, please cite the paper as follows:

```
@article{austnes2024probabilistic,
  title={Probabilistic Load Forecasting of Distribution Power Systems based on Empirical Copulas},
  author={Austnes, P{\aa}l Forr and Garc{\'\i}a-Pareja, Celia and Nobile, Fabio and Paolone, Mario},
  journal={arXiv preprint arXiv:2310.03657},
  year={2024}
}
```
[1] Nespoli, L., Medici, V., Lopatichki, K., & Sossan, F. (2020). Hierarchical demand forecasting benchmark for the distribution grid. Electric Power Systems Research, 189, 106755. https://doi.org/10.1016/j.epsr.2020.106755

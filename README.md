# Hybrid Modeling of Evapotranspiration: Inferring Stomatal and Aerodynamic Resistances Using Combined Physics-Based and Machine Learning

## Description

This repository contains the code for the paper:

*ElGhawi, R., Kraft, B., Reimers, C., Reichstein, M., Körner, M., Gentine, P., & Winkler, A. J. (2023). Hybrid modeling of evapotranspiration: inferring stomatal and aerodynamic resistances using combined physics-based and machine learning. Environmental Research Letters, 18(3), 034039. https://doi.org/10.1088/1748-9326/ACBBE0*

The datasets used cannot be shared but all datasets are referenced in the paper. The simulated variables are available and linked in the paper.

We share the code for transparency and to demonstrate the concept of hybrid modeling. However, the code is tweaked to our environment and data infrastructure, it cannot be run without adaptions.

* All data paths need to be adapted to your data infrastructure.

**We are happy to answer your questions, discuss, and collaborate!**

Contact: relghawi@bgc-jena.mpg.de

## Structure

* Data preprocessing of the individual datasets: `Hybrid_ET/Preprocessing/`
* Data is compiled into a "netcdf" files using `Hybrid_ET/Preprocessing/Flux_mult.py`.
* The standard hybrid model can be found here: `Hybrid_ET/Models/Under-constrained hybrid model.py`
* The hybrid model is trained `Hybrid_ET/Training/train_hyb_uncon.py `

## Citation

```tex
@article{10.1088/1748-9326/ACBBE0, author = {ElGhawi, Reda and Kraft, Basil and Reimers, Christian and Reichstein, Markus and Körner, Marco and Gentine, Pierre and Winkler, Alexander J},
title = {Hybrid Modeling of Evapotranspiration: Inferring Stomatal and Aerodynamic Resistances Using Combined Physics-Based and Machine Learning}, 
journal = {Environmental Research Letters}, year = {2023}, 
DOI = {10.1088/1748-9326/ACBBE0}, 
url = {https://doi.org/10.1088/1748-9326/ACBBE0}}
```


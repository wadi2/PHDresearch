# COVID-19 Immunity Profiling using Random Forest

## Overview
This repository contains a **Jupyter Notebook** implementing a **Random Forest classifier** for immunity profiling in **COVID-19 screening**. The code classifies **unknown samples** into predefined immunity categories using **known sample data** from `.csv` files.

This work is based on the following publication:

🔗 **[Machine-learning-aided multiplexed nanoplasmonic biosensor for COVID-19 population immunity profiling](https://pubs.rsc.org/en/content/articlehtml/2023/sd/d3sd00081h)** (RSC Sensor & Diagnostics, 2023)

## Project Workflow
The notebook follows these key steps:
1. **Load Data**: Reads processed `.csv` files containing labeled and unknown sample data.
2. **Train Random Forest Model**: Initializes and fits a **Random Forest classifier**.
3. **Make Predictions**: Classifies unknown samples based on trained model.

## Repository Contents
- `notebooks/` - Contains the Jupyter Notebook `immunityProfiling_COVID19Project_code.ipynb`.
- `data/` - Sample `.csv` datasets used for training and classification.
- `figures/` - Figures from the publication.


## Citation
If you use this repository, please cite the original paper:
```bibtex
@article{immunity_profiling_2023,
  author = {Beisenova, A., Adi, W., Bashar, S. J., Velmurugan, M., Germanson, K. B., Shelef, M. A., & Yesilkoy, F.},
  title = {Machine learning-based prediction of chemical properties from molecular structures},
  journal = {RSC Sensors & Diagnostics},
  year = {2023},
  url = {https://pubs.rsc.org/en/content/articlehtml/2023/sd/d3sd00081h}
}
```


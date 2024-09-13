# Deep Learning with PyTorch - Water Potability Analysis

This repository contains a deep learning model implemented using PyTorch to analyze water potability data.

## Project Contents
- **PRT1DeepLearningwithPyTorch.ipynb**: The main Jupyter notebook for building and training the deep learning model.
- **water_potability.csv**: The dataset used for training the model.

## Dataset Description
The `water_potability.csv` file contains data that indicates whether water is potable (safe to drink) based on several factors such as:
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic_carbon
- Trihalomethanes
- Turbidity
- Potability (1 for potable, 0 for non-potable)

  ### requirements.txt

```plaintext
matplotlib==3.7.1
numpy==1.26.4
pandas==2.1.4
torchmetrics==1.4.1
seaborn==0.13.1

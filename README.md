# HMI

PyTorch implementation of Hyperbolic Embedding Inference for Structured Multi-Label Prediction

## Requirements

- torch>=1.8.0
- geoopt (`$ pip install git+https://github.com/geoopt/geoopt.git`)
- numpy
- scipy
- pandas
- tqdm

## Instructionå

To run HMI on "derisi_FUN" dataset, run the following scripts:

nohup python run.py --dataset derisi_FUN > logs/derisi_FUN.txt 2>&1 &


## Jupyter notebooks

/analysis/HMI-example.ipynb provides a toy example of HMI for embedding HEX graph.

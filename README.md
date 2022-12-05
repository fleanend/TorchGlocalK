# TorchGLocal-K: Global and Local Kernels for Recommender Systems in Torch!

This repository contains unofficial PyTorch code for paper [GLocal-K: Global and Local Kernels for Recommender Systems](https://arxiv.org/pdf/2108.12184.pdf).

You may find the [original code in TensorFlow here](https://github.com/usydnlp/Glocal_K/blob/main/README.md).

![GLocal_K_overview](https://user-images.githubusercontent.com/41948621/131093771-39d86126-6be6-4fc8-bcda-3eab8fd2c181.png)

## 1. Introduction
The notebooks in this repo provides the porting of the published experiment translated into Torch and with a more Deep Learning style inspired approach.

Original_Glocal_K.ipynb is the actual implementation of the original code
Glocal_K.ipynb is a variation which I found to perform better on Torch

## 2. Setup
Open the chosen notebook in Google Colab

## 3. Requirements
* numpy
* scipy
* torch

## 4. Run
Run all cells

## 5. Results
The final results fall short of the published ones, the architecture was slightly modified by adding dropout layers and using AdamW optimizer, translating the architecture, optimizer and training routine exactly resulted in worse performance.

## 6. Data References
1. Harper, F. M., & Konstan, J. A. (2015). The movielens datasets: History and context. *Acm transactions on interactive intelligent systems (tiis)*, 5(4), 1-19.
2. Monti, F., Bronstein, M. M., & Bresson, X. (2017, December). Geometric matrix completion with recurrent multi-graph neural networks. In *Proceedings of the 31st International Conference on Neural Information Processing Systems* (pp. 3700-3710).

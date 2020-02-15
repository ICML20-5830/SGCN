# SGCN

Open-sourced implementation for ICML20 paper (5830) "On the Importance of Sampling in Learning Graph Convolutional Networks: 
Convergence Analysis and Variance Reduction".

Please check `example.ipynb` for details. Before getting started, please read the following instructions.

## Experiment setup
- Go to the root folder, run `mkdir ./results` and `mkdir ./data` to create folders for saving experiment results and training data respectively.
- Download data from [google drive link](https://drive.google.com/drive/folders/1qrFuQOxrbaDziJFeEkpAiXmL_C8dlk3K?usp=sharing), and put the training data (e.g., Pubmed, Flickr, Reddit, PPI) into folder `./data`.

## Algorithms
- "sgcn_pplus_0" refers to the zeroth-order only
- "sgcn_pplus_1" refers to the first-order only
- "sgcn_pplus_01" refers to the doubly variance reduction

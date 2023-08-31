# ASTGCN-pytorch-ipynb
implementation of ASTGCN
# Project introduction
This project aims to reproduce the ASTGCN (Attention-based Spatial-Temporal Graph Convolutional Network) model presented in a research paper. The ASTGCN model is designed to tackle spatio-temporal data analysis by incorporating attention mechanisms within a graph convolutional neural network framework. This project focuses on re-implementing the model and exploring its performance on a specific task.
# Model introductions
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/e3e8bd1c-977d-47b8-83d8-71db34baf528)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/f1d4eaa5-79ef-463b-a03b-ade428f54141)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/693709e1-bc1c-4e13-b484-db323737d6e3)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/d3cf2020-fd8c-41fd-880c-9bdc4dae4c50)
# Results for 1h prediction
data:PEMS04
Mstgcn :all MAE: 22.56 all RMSE: 35.52
Astgcn :all MAE: 22.12 all RMSE: 35.11
stgcn :all MAE: 25.15 all RMSE: 38.29(from paper)
MAE DROP:12.04% RMSE DROP:8.3%
# Visualization
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/92481543-5ab5-474f-b1b0-6fe9e3addea8)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/cc96afa9-d7a6-41c7-8ddf-8c7d9d45b6a9)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/eab96148-d59f-414d-b2f3-601aa05cd457)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/78d5316f-76be-49fa-b13d-91c0a453f468)
![image](https://github.com/qingqisqq/ASTGCN-pytorch-ipynb/assets/143696962/27123f32-d617-4bf8-922f-01cec0abc1c4)


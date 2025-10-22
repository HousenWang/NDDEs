# Physics-informed Neural Network for Delay Differential Equations (PINN-DDEs)

## Introduction

This repository contains the implementation of physics-informed neural network for delay differential equations, a deep neural network framework designed to solve both forward and inverse problems related to delay differential equations.  This approach integrates DDEs into neural networks, allowing for the accommodation of diverse requirements such as initial conditions, control equations, and known data. 

For more information, please refer to our paper: 

- H. Wang, Y. Chen, S. Cao, X. Wang, and Q. Liu, "A deep neural network framework for solving forward and inverse problems in delay differential equations," *Journal of Computational and Applied Mathematics*, vol. 477, p. 117154, 2026, doi: 10.1016/j.cam.2025.117154.

If you have any questions about this repository, please contact Housen Wang ([wanghs1011111@126.com](mailto:wanghs1011111@126.com)).

## Environment Configuration

This project was developed using Baidu's PaddlePaddle AI Studio with the following configuration:

- **GPU**: Tesla V100
- **Video Memory**: 32GB
- **CPU**: 4 Cores
- **RAM**: 32GB
- **Disk**: 100GB

You can use the following link to access Baidu's PaddlePaddle AI Studio.

 ![Static Badge](https://img.shields.io/badge/Baidu-AI_Studio-brightgreen?style=plastic&logo=baidu&link=https%3A%2F%2Faistudio.baidu.com%2Findex)


## Code
The code for our numerical experiments can be found in the [`numerical_experiments`](https://github.com/HousenWang/NDDEs/tree/mian/numerical_experiments) directory and the Python libraries required to run the experiments are listed in the [`required_packages`](https://github.com/HousenWang/NDDEs/tree/mian/required_packages)
 file.








# Neural Delay Differential Equations (NDDEs)

## Introduction

This repository contains the implementation of Neural Delay Differential Equations (NDDEs), a deep neural network framework designed to solve both forward and inverse problems related to delay differential equations (DDEs).  This approach integrates DDEs into neural networks, allowing for the accommodation of diverse requirements such as initial conditions, control equations, and known data. 

For more information, please refer to our paper: 

- Wang, H., Chen, Y., Cao, S., Wang, X., & Liu, Q. "[A Deep Neural Network Framework for Solving Forward and Inverse Problems in Delay Differential Equations](https://arxiv.org/abs/2408.09202)" arXiv preprint arXiv. (2024).

If you have any questions about this repository, please contact Housen Wang ([wanghs1011111@163.com](mailto:wanghs1011111@163.com)).

## Environment Configuration

This project was developed using Baidu's PaddlePaddle AI Studio with the following configuration:

- **GPU**: Tesla V100
- **Video Memory**: 32GB
- **CPU**: 4 Cores
- **RAM**: 32GB
- **Disk**: 100GB

You can use the following link to access Baidu's PaddlePaddle AI Studio.

 ![Static Badge](https://img.shields.io/badge/Baidu-AI_Studio-brightgreen?style=plastic&logo=baidu&link=https%3A%2F%2Faistudio.baidu.com%2Findex)

## Installation

**Clone the repository:**

```
git clone https://github.com/HousenWang/NDDEs.git
cd NDDEs
```

**Install required packages:**

To ensure your environment is fully compatible with this project, you can download a pre-packaged set of all required libraries from the link below. This file contains all necessary dependencies as they were configured and used in the development environment.

[Download Packaged Dependencies](https://drive.google.com/file/d/1aZzYxiEs0ugrfa6piFoQye_fBNg3tsWJ/view?usp=sharing "Download dependencies")

## Code

The code for our numerical experiments can be found in the [`work`](https://github.com/HousenWang/NDDEs/tree/master/work) directory.








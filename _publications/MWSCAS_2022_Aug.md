---
title: "Hardware Acceleration in Large-Scale Tensor Decomposition for Neural Network Compression"
collection: publications
permalink: /publication/MWSCAS_Aug_2022
date: Aug., 2022
venue: '2022 IEEE 65th International Midwest Symposium on Circuits and Systems (MWSCAS)'
---
<p align="center">
<img src='/images/publications/Tensor_Decomposition.jpg' width='600' > 
</p><br>

<br>
**Abstract:** A tensor is a multi-dimensional array, which is embedded for neural networks. The multiply-accumulate (MAC) operations involved in a large-scale tensor introduces high computational complexity. Since the tensor usually features a low rank, the computational complexity can be largely reduced through canonical polyadic decomposition (CPD). This work presents an energy-efficient hardware accelerator that implements randomized CPD in large-scale tensors for neural network compression. A mixing method that combines the Walsh-Hadamard transform and discrete cosine transform is proposed to replace the fast Fourier transform with faster convergence. It reduces the computations for transformation by 83%. 75% of computations for solving the required least squares problem are also reduced. The proposed accelerator is flexible to support tensor decomposition with a size of up to 512×512×9×9. Compared to the prior dedicated processor for tensor computation, this work support larger tensors and achieves a 112× lower latency given the same condition.

[Paper Link](http://jacky1229.github.io/files/publication_papers/Hardware_Acceleration_in_Large-Scale_Tensor_Decomposition_for_Neural_Network_Compression.pdf)<br>
Recommended citation: C. -C. Kao, Y. -Y. Hsieh, C. -H. Chen and C. -H. Yang, "Hardware Acceleration in Large-Scale Tensor Decomposition for Neural Network Compression," <i>2022 IEEE 65th International Midwest Symposium on Circuits and Systems (MWSCAS)<i>, 2022, pp. 1-4
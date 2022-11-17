---
title: "CP Decomposition Accelerator"
collection: Research
permalink: /research/CPD
venue: "Digital Circuits and Systems Laboratory, National Taiwan University"
---

<p align="center">
<img src='/images/publications/Tensor_Decomposition.jpg' width='600' > 
</p><br>

<br>

A tensor is an array with multiple dimensions. It has been applied to many applications, especially for deep learning due to the structure of neural networks with multiple dimensions,contributed by the dimensions of feature map and filter.
The tensors involved in these neural networks usually feature a low-rank property. 
This property can be leveraged to compress the neural networks, thereby reducing their computational complexity and memory usage.
The canonical polyadic decomposition (CPD) is one generalization of singular value decomposition (SVD) and it is widely used for low-rank tensor decomposition.
CPD computation for high-dimension tensor is time consuming; therefore, dedicated hardware acceleration is critical.
We proposed a large-scale CPD accelerator based on randomized CP decomposition.
The combination of Walsh–Hadamard transform and discrete cosine transform was proposed to replace original fast Fourier transform, which reduce memory usage and computational complexity.
The proposed accelerator can support four-dimensional tensor, and it achieves lower latency than previous works.

This work was published in <b><i>  2022 IEEE 65th International Midwest Symposium on Circuits and Systems </i></b>
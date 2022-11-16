---
title: "Hybrid Precoding Processor for mmWave Massive MIMO System"
collection: Research
permalink: /research/hybrid_precoding
venue: Digital Circuits and Systems Laboratory, National Taiwan University"
date: 2019-02-01
---

In mmWave MIMO where the number of antennas to be deployed is often massive, full baseband processing can be very expensive.
A more practical way to implement the precoding in mmWave MIMO is through hybrid precoding.
The hybrid precoder consists of a two-stage concatenated structure, where an analog precoder is performed at the RF front-end using phase-shifters while a dimension-reduced digital precoder is performed at baseband. 
Existing designs in previous works are mostly based on the OMP algorithm, which has some performance loss due to restricting the space of feasible analog precoding solutions.
In this work, we designed a hybrid precoding adopting based on alternating minimization algorithm for better spectral efficiency.
We proposed a polar decomposition based algoritm the replace orignal SVD operation for implementing in a highly parallel manner.
The proposed hybrid precoding processor is able to support 6more antennas with a higher flexibility in the number of data streams and RF chains.
It can achieve better area and energy efficiency than previous works.

This work was published in <b><i> IEEE Transactions on Circuits and Systems I: Regular Papers </i></b
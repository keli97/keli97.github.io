---
title: "QLEC: A Machine-Learning-Based Energy-Efficient Clustering Algorithm to Prolong Network Lifespan for IoT in High-Dimensional Space"
collection: publications
permalink: /publication/2019-05-21-QLEC-A-Machine-Learning-Based-Energy-Efficient-Clustering-Algorithm-to-Prolong-Network-Lifespan-for-IoT-in-High-Dimensional-Space
excerpt: 'August 5–8, 2019, Kyoto, Japan. Keyword: IoT, Energy-Efficient Clustering, Q-learning, Lifespan-Extended Network, High-Dimensional Space'
date: 2019-05-21
venue: 'The International Conference on Parallel Processing (ICPP)'
paperurl: 'https://dl.acm.org/doi/10.1145/3337821.3337926'
citation: '<u>Ke Li</u>, Haowei Huang, Xiaofeng Gao, Fan Wu, and Guihai Chen. 2019. QLEC: A Machine-Learning-Based Energy-Efficient Clustering Algorithm to Prolong Network Lifespan for IoT in High-Dimensional Space. In <i>Proceedings of the 48th International Conference on Parallel Processing (ICPP)</i>. Association for Computing Machinery, New York, NY, USA, Article 105, 1–10.'
teaser_gif: /files/pubs/qlec.png
---
August 5–8, 2019, Kyoto, Japan  
Keyword: IoT, Energy-Efficient Clustering, Q-learning, Lifespan-Extended Network, High-Dimensional Space

With the emergence of Internet of Things (IoT), many battery-operated sensors are deployed in different applications to collect, process, and analyze useful information. In these applications, sensors are often grouped into different clusters to support higher scalability and better data aggregation. Clustering based on energy distribution among nodes can reduce energy consumption and prolong the network lifespan. In our paper, we propose a machine-learning-based energy-efficient clustering algorithm named QLEC to select cluster heads in high-dimensional space and help non-cluster-head nodes route packets. QLEC first selects cluster heads based on their residual energy through successive rounds. Besides, we prove the optimal cluster number in a high-dimensional wireless network and adopt it in our QLEC algorithm. Furthermore, Q-learning method is utilized to maximize residual energy of the network while routing packets from sensors to the base station (BS). The energy-efficient clustering problem in high dimensional space can be formed as an NP-Complete problem and QLEC is proved to solve it in the running time O(kX), where k is the cluster number and X is the number of updates Q-learning needs to converge. Extensive simulations and experiments based on a large-scale dataset show that the proposed scheme outperforms a newly proposed FCM-based algorithm and k-means clustering in terms of network lifespan, packet delivery rate, and transmission latency. To the best of our knowledge, this is the first work adopting Q-learning method in clustering problems in high-dimensional space.

<!--Improved Distributed Energy Efficient Clustering (DEEC) algorithm with energy constraints and cluster coverage ranges of sensors in 3-dimensional WSNs taken into consideration.-->
<!--Adopted Q-learning scheme to choose cluster heads for routing packets of each sensor.-->
<!--Solved the Energy-Efficient Clustering Problem (EECP), which is an NP-Complete problem in the running time O(kX), where k is the cluster number and X is the number of updates that Q-learning needs to converge.-->
<!--Conducted experiments with the algorithm and outperformed k-means clustering and an FCM-based algorithm in terms of network lifespan, packet delivery rate, and transmission latency.-->

<!--[Download paper here](https://dl.acm.org/doi/10.1145/3337821.3337926)-->

<!--Recommended citation: <u>Ke Li</u>, Haowei Huang, Xiaofeng Gao, Fan Wu and Guihai Chen. 2019. QLEC: A Machine-Learning-Based Energy-Efficient Clustering Algorithm to Prolong Network Lifespan for IoT in High-Dimensional Space. <i>The 48th International Conference on Parallel Processing (ICPP)</i>, Article No. 105, Pages 1–10.-->

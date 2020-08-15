---
title: "Robust Graph Representation Learning via Neural Sparsification"
date: 2020-07-01
publishDate: 2020-08-09T05:55:58.252795Z
authors: ["Cheng Zheng", "Bo Zong", "Wei Cheng", "Dongjin Song", "Jingchao Ni", "Wenchao Yu", "Haifeng Chen", "Wei Wang"]
publication_types: ["1"]
abstract: "Graph representation learning serves as the core of important prediction tasks, ranging from product recommendation to fraud detection. Real life graphs usually have complex information in the local neighborhood, where each node is described by a rich set of features and connects to dozens or even hundreds of neighbors. Despite the success of neighborhood aggregation in graph neural networks, task-irrelevant information is mixed into nodes’ neighborhood, making learned models suffer from sub-optimal generalization performance. In this paper, we present NeuralSparse, a supervised graph sparsification technique that improves generalization power by learning to remove potentially task-irrelevant edges from input graphs. Our method takes both structural and non-structural information as input, utilizes deep neural networks to parameterize sparsification processes, and optimizes the parameters by feedback signals from downstream tasks. Under the NeuralSparse framework, supervised graph sparsification could seamlessly connect with existing graph neural networks for more robust performance. Experimental results on both benchmark and private datasets show that NeuralSparse can yield up to 7.2% improvement in testing accuracy when working with existing graph neural
networks on node classification tasks."
featured: True
publication: "*Proceedings of the 37th International Conference on Machine Learning (ICML)*"
---

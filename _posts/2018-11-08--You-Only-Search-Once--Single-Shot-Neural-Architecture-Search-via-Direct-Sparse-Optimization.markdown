---
layout: post
title:  " You Only Search Once: Single Shot Neural Architecture Search via Direct Sparse Optimization"
date:   2018/11/08
categories: none
---



### You Only Search Once: Single Shot Neural Architecture Search via Direct Sparse Optimization



* Zhang, Xinbang; 

* Huang, Zehao; 

* Wang, Naiyan; 





**Abstract**:  Recently Neural Architecture Search (NAS) has aroused great interest in both academia and industry, however it remains challenging because of its huge and non-continuous search space. Instead of applying evolutionary algorithm or reinforcement learning as previous works, this paper proposes a Direct Sparse Optimization NAS (DSO-NAS) method. In DSO-NAS, we provide a novel model pruning view to NAS problem. In specific, we start from a completely connected block, and then introduce scaling factors to scale the information flow between operations. Next, we impose sparse regularizations to prune useless connections in the architecture. Lastly, we derive an efficient and theoretically sound optimization method to solve it. Our method enjoys both advantages of differentiability and efficiency, therefore can be directly applied to large datasets like ImageNet. Particularly, On CIFAR-10 dataset, DSO-NAS achieves an average test error 2.84\%, while on the ImageNet dataset DSO-NAS achieves 25.4\% test error under 600M FLOPs with 8 GPUs in 18 hours. 



 [https://arxiv.org/abs/1811.01567v1](https://arxiv.org/abs/1811.01567v1) 


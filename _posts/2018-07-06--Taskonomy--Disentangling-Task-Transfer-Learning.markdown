---
layout: post
title:  " Taskonomy: Disentangling Task Transfer Learning"
date:   2018/07/06
categories: none
---



### Taskonomy: Disentangling Task Transfer Learning



* Zamir, Amir; 

* Sax, Alexander; 

* Shen, William; 

* Guibas, Leonidas; 

* Malik, Jitendra; 

* Savarese, Silvio; 





**Abstract**:  Do visual tasks have a relationship, or are they unrelated? For instance, could having surface normals simplify estimating the depth of an image? Intuition answers these questions positively, implying existence of a structure among visual tasks. Knowing this structure has notable values; it is the concept underlying transfer learning and provides a principled way for identifying redundancies across tasks, e.g., to seamlessly reuse supervision among related tasks or solve many tasks in one system without piling up the complexity. We proposes a fully computational approach for modeling the structure of space of visual tasks. This is done via finding (first and higher-order) transfer learning dependencies across a dictionary of twenty six 2D, 2.5D, 3D, and semantic tasks in a latent space. The product is a computational taxonomic map for task transfer learning. We study the consequences of this structure, e.g. nontrivial emerged relationships, and exploit them to reduce the demand for labeled data. For example, we show that the total number of labeled datapoints needed for solving a set of 10 tasks can be reduced by roughly 2/3 (compared to training independently) while keeping the performance nearly the same. We provide a set of tools for computing and probing this taxonomical structure including a solver that users can employ to devise efficient supervision policies for their use cases. 



 [https://arxiv.org/abs/1804.08328](https://arxiv.org/abs/1804.08328) 


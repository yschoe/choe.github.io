---
layout: post
title:  " Dataset Distillation"
date:   2018/11/30
categories: none
---



### Dataset Distillation



* Wang, Tongzhou; 

* Zhu, Jun-Yan; 

* Torralba, Antonio; 

* Efros, Alexei A.; 





**Abstract**:  Model distillation aims to distill the knowledge of a complex model into a simpler one. In this paper, we consider an alternative formulation called {\em dataset distillation}: we keep the model fixed and instead attempt to distill the knowledge from a large training dataset into a small one. The idea is to {\em synthesize} a small number of data points that do not need to come from the correct data distribution, but will, when given to the learning algorithm as training data, approximate the model trained on the original data. For example, we show that it is possible to compress $60,000$ MNIST training images into just $10$ synthetic {\em distilled images} (one per class) and achieve close to original performance with only a few steps of gradient descent, given a particular fixed network initialization. We evaluate our method in a wide range of initialization settings and with different learning objectives. Experiments on multiple datasets show the advantage of our approach compared to alternative methods in most settings. 



 [https://arxiv.org/abs/1811.10959v1](https://arxiv.org/abs/1811.10959v1) 


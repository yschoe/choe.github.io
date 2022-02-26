---
layout: post
title:  "[Hopfield] Unsupervised learning by competing hidden units"
date:   2019/04/10
categories: none
---



Unsupervised learning by competing hidden units

Dmitry Krotov and John J. Hopfield



Abstract

It is widely believed that end-to-end training with the backpropagation algorithm is essential for learning good feature detectors in early layers of artificial neural networks, so that these detectors are useful for the task performed by the higher layers of that neural network. At the same time, the traditional form of backpropagation is biologically implausible. In the present paper we propose an unusual learning rule, which has a degree of biological plausibility and which is motivated by Hebb’s idea that change of the synapse strength should be local—i.e., should depend only on the activities of the pre- and postsynaptic neurons. We design a learning algorithm that utilizes global inhibition in the hidden layer and is capable of learning early feature detectors in a completely unsupervised way. These learned lower-layer feature detectors can be used to train higher-layer weights in a usual supervised way so that the performance of the full network is comparable to the performance of standard feedforward networks trained end-to-end with a backpropagation algorithm on simple tasks.



[https://www.pnas.org/content/116/16/7723](https://www.pnas.org/content/116/16/7723)





 


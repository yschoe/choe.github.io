---
layout: post
title:  " Data Augmentation by Pairing Samples for Images Classification"
date:   2018/01/12
categories: none
---



### Data Augmentation by Pairing Samples for Images Classification



* Inoue, Hiroshi; 





**Abstract**:  Data augmentation is a widely used technique in many machine learning tasks, such as image classification, to virtually enlarge the training dataset size and avoid overfitting. Traditional data augmentation techniques for image classification tasks create new samples from the original training data by, for example, flipping, distorting, adding a small amount of noise to, or cropping a patch from an original image. In this paper, we introduce a simple but surprisingly effective data augmentation technique for image classification tasks. With our technique, named SamplePairing, we synthesize a new sample from one image by overlaying another image randomly chosen from the training data (i.e., taking an average of two images for each pixel). By using two images randomly selected from the training set, we can generate $N^2$ new samples from $N$ training samples. This simple data augmentation technique significantly improved classification accuracy for all the tested datasets; for example, the top-1 error rate was reduced from 33.5% to 29.0% for the ILSVRC 2012 dataset with GoogLeNet and from 8.22% to 6.93% in the CIFAR-10 dataset. We also show that our SamplePairing technique largely improved accuracy when the number of samples in the training set was very small. Therefore, our technique is more valuable for tasks with a limited amount of training data, such as medical imaging tasks. 



 [https://arxiv.org/abs/1801.02929v1](https://arxiv.org/abs/1801.02929v1) 


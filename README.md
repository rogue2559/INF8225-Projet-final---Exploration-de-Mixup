# INF8225 Projet final - Exploration de Mixup

Polytechnique Montréal.

Contributed by Wail AYAD, Mohamed BEN AHMED DAHO, Yuanchao MA and Alexandru TRANDAFIR

Data augmentation methods for deep convolutional networks have been a critical factor in order to address some of the problems these architectures present. Mainly, the methods strive to improve generalization and better handling of adversarial examples, as well as to reduce the amount of training data required to achieve peak performance. 

The article [*Mixup: Beyond Empirical Risk Minimization*](https://arxiv.org/abs/1710.09412) proposed a method who used linear combination of training samples and its labels in order to enhance performance. This article then inspired, several variations : [*CutMix*](https://arxiv.org/abs/1905.04899), [*Manifold Mixup*](https://arxiv.org/abs/1806.05236) and [*AugMix*](https://arxiv.org/abs/1912.02781). 

We compared these four methods by training convolutional networks ResNet and DenseNet on datasets CIFAR-10 and CIFAR-100 in order to get a better understanding of their respective pros and cons. 

The results show that CutMix performs best among the four candidates on image classification task, while Manifold Mixup also shows relatively good performance. Given that CutMix, Manifold Mixup and AugMix are not based on exactly the same theory, future work could attempt to test a fusion of these three.


## Dataset

CIFAR-10, CIFAR-100

## Results

![image](https://user-images.githubusercontent.com/33432338/166124008-a17186e8-0122-4e3b-bd97-b126a0a2d061.png)

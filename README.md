# INF8225 Projet final - Exploration de Mixup

Polytechnique Montréal.

Contributed by Wail AYAD, Mohamed BEN AHMED DAHO, Yuanchao MA and Alexandru TRANDAFIR

Data augmentation methods for deep convolutional networks have been a critical factor in order to address some of the problems these architectures present. Mainly, the methods strive to improve generalization and better handling of adversarial examples, as well as to reduce the amount of training data required to achieve peak performance. The article *Mixup: Beyond Empirical Risk Minimization* proposed a method who used linear combination of training samples and its labels in order to enhance performance. This article then inspired, several variations : *CutMix*, *Manifold Mixup* and *AugMix*. We compared these four methods by training convolutional networks ResNet and DenseNet on datasets CIFAR-10 and CIFAR-100 in order to get a better understanding of their respective pros and cons. The results show that CutMix performs best among the four candidates on image classification task, while Manifold Mixup also shows relatively good performance. Given that CutMix, Manifold Mixup and AugMix are not based on exactly the same theory, future work could attempt to test a fusion of these three.

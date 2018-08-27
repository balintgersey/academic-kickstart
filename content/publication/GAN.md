+++
title = "Generative Adversarial Networks and their application in Finance"
date = 2018-05-04T00:00:00
math = false
highlight = true

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = APA
#   3 = MLA
list_format = 1

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++

<div class="pub-abstract" itemprop="text">
  
  My master thesis focuses on one of the dominant approaches to generative modelling, generative adversarial
  networks (GANs). After a brief description of fundamental notions of deep learning such as feed-forward,
  convolutional and recurrent neural networks, I review stochastic gradient descent and prove the convergence
  of it under the so called slowly decaying learning rates condition. In the main chapter about GANs, I review
  and discuss recent theoretical development and I present some pathological behaviours that occur when
  training a GAN in practice such as the problems of mode collapse and vanishing gradient. Finally, I briefly
  review various solutions to avoid these problems, including a shallow discussion of the Wasserstein GAN. I
  also implemented several GANs. I first train a GAN on sinusoidal curves. Then I train another GAN on the
  MNIST dataset. Finally, I also implement a DCGAN and train it on the CIFAR-10 dataset. For illustration
  purposes, I used different deep learning frameworks (Keras, TensorFlow and Pytorch) for each of them.
  Finally, in the last chapter, I propose a new way to generate artificial financial time series using Recurrent
  Generative Adversarial Networks. The idea is to replace usual Monte Carlo simulations (which have
  probabilistic assumptions which are not always met in reality) with simulations with a generator trained with
  a GAN on a financial dataset. The RGAN model and implementation is based on the method of Hyland et al.
  for generative modelling of time series.

  My master thesis is available 
  <a href ="https://www.researchgate.net/publication/326676131_Generative_Adversarial_Networks"> here <a>
 
</div>
<div class="pub-authors" itemprop="author">
     Author: Balint Gersey
 </div>


<div class="pub-links">
  <a class="btn btn-primary btn-outline btn-xs" href="https://www.researchgate.net/publication/326676131_Generative_Adversarial_Networks" target="_blank" rel="noopener">
  Preprint
  </a>

  <a class="btn btn-primary btn-outline btn-xs" href="https://github.com/balintgersey/Generative-Adversarial-Networks-for-financial-time-series-generation" target="_blank" rel="noopener">
  Code
  </a>
 </div>

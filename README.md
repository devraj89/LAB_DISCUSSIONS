# LAB_DISCUSSIONS
discussions regarding random deep learning papers on Lab

21st Feb 2019
-----------------

Deep Learning for Case-Based Reasoning through Prototypes: A Neural Network that Explains Its Predictions
-----------------------------------------------------------------------------------------------------------------------

https://arxiv.org/pdf/1710.04806.pdf

code : https://github.com/OscarcarLi/PrototypeDL

- a method that can explain its predictions 

- a very unique take on the deep learning neural based frameworks 

26th Feb 2019
-----------------

Tutorial on VAE
-----------------------------------------------------------------------------------------------------------------------

Let me first read it up from different blogs so that I must first understand it

- http://kvfrans.com/variational-autoencoders-explained/
- https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf
- https://jaan.io/what-is-variational-autoencoder-vae-tutorial/
- https://wiseodd.github.io/techblog/2016/12/10/variational-autoencoder/ (KERAS CODE)
- https://wiseodd.github.io/techblog/2017/01/24/vae-pytorch/ (PYTORCH CODE)
- https://arxiv.org/pdf/1606.05908.pdf
- https://github.com/pytorch/examples/tree/master/vae (OFFICIAL CODE)
- https://vxlabs.com/2017/12/08/variational-autoencoder-in-pytorch-commented-and-annotated/ (OFFICIAL CODE ANNOTATED)

Only Doubt is this -- since during training we are using a KL divergence to minimize the encoder distribution
with a simple normal distribution and during inferencing we are sampling from N(0,1) so how does it work exactly ?
meaning that how does sampling from N(0,1) inherit the encoding properties of the encoder Q(z|x) ?

also understood how the different losses behave and why it is a lower bound.


28th Feb 2019
-----------------

by Titir - Memorization Precedes Generation: Learning Unsupervised GANs with Memory Networks
-----------------------------------------------------------------------------------------------------------------------

https://openreview.net/forum?id=rkO3uTkAZ

https://github.com/whyjay/memoryGAN

- a very interesting paper with a memory module consisting of keys, values , age of memory module and frequency of occurance of memory modules 

- a new distribution VMF to measure the distance between the keys and the generated data

- discussions regarding the bayes rule are provided in the open review 

by Supritam - Adversarial Metric Learning
-----------------------------------------------------------------------------------------------------------------------

https://www.ijcai.org/proceedings/2018/0279.pdf

- the metric is supposed to know how to make the positive pair distance small and the negative pair distance bigger 

- generate pairs of sample (both pos and negative) which are wrongly classified by the metric

- train the gen and metric in an adversarial fashion 


5th March 2019
-----------------

InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets
--------------------------------------------------------------------

https://arxiv.org/pdf/1606.03657.pdf

https://wiseodd.github.io/techblog/2017/01/29/infogan/ -- some more explanations

https://github.com/pianomania/infoGAN-pytorch

https://github.com/eriklindernoren/PyTorch-GAN#infogan

I have understood all the derivations. Some helpful hints are here:

Learning to Discover Cross-Domain Relations with Generative Adversarial Networks
--------------------------------------------------------------------

https://arxiv.org/abs/1703.05192

https://github.com/carpedm20/DiscoGAN-pytorch




8th March 2019
-----------------

Good Semi-Supervised Learning That Requires a Bad GAN
--------------------------------------------------------------------

https://arxiv.org/abs/1705.09783

https://github.com/kimiyoung/ssl_bad_gan

What is a teacher student model in a Convolutional neural network?
--------------------------------------------------------------------

need to list down the references for this later 



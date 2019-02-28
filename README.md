# LAB_DISCUSSIONS
discussions regarding random deep learning papers on Lab

21st Feb 2019
-----------------

Deep Learning for Case-Based Reasoning through Prototypes: A Neural Network that Explains Its Predictions

https://arxiv.org/pdf/1710.04806.pdf

code : https://github.com/OscarcarLi/PrototypeDL

- a method that can explain its predictions 

- a very unique take on the deep learning neural based frameworks 

26th Feb 2019
-----------------

Tutorial on VAE

Let me first read it up from different blogs so that I must first understand it

http://kvfrans.com/variational-autoencoders-explained/
https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf
https://jaan.io/what-is-variational-autoencoder-vae-tutorial/
https://wiseodd.github.io/techblog/2016/12/10/variational-autoencoder/ (KERAS CODE)
https://wiseodd.github.io/techblog/2017/01/24/vae-pytorch/ (PYTORCH CODE)
https://arxiv.org/pdf/1606.05908.pdf
https://github.com/pytorch/examples/tree/master/vae (OFFICIAL CODE)
https://vxlabs.com/2017/12/08/variational-autoencoder-in-pytorch-commented-and-annotated/ (OFFICIAL CODE ANNOTATED)

Only Doubt is this -- since during training we are using a KL divergence to minimize the encoder distribution
with a simple normal distribution and during inferencing we are sampling from N(0,1) so how does it work exactly ?
meaning that how does sampling from N(0,1) inherit the encoding properties of the encoder Q(z|x) ?

also understood how the different losses behave and why it is a lower bound.

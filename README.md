# GAN-for-mnist-generation
steps:

1.import libraries and process data

2.create g=generator model and d=discriminator model...(compile d model)#use leakyRelu

3.concatenate g and d model into a GAN model

4.for certain epochs,train d by inputtting noise+mnist data

5.train g with noise as input and images as output...viz.it will match Noise input features to image arraya output

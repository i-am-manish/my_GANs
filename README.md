# GANs
steps:

1.import libraries and process data

2.create g=generator model and d=discriminator model...(compile d model)#use leakyRelu

3.concatenate g and d model into a GAN model

4.for certain epochs,train d ad input=noise_data(make G predict on it)+mnist_data

5.train g with noise as input and images as output...viz.it will match Noise input features to image arraya output

6.for GANS we atleast need 10000 epochs...so try more iterations and optimization

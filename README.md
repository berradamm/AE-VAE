# Auto Encoder 
An Autocoder for hande-written numbers generation implemented with Pytorch 
## The dataset
The most mainstream one : MNIST
## Results

![sample_continuous](https://user-images.githubusercontent.com/45148200/49581255-a45c9c00-f951-11e8-9675-69686ef5ad6a.png)

# VAE-Variational_AutoEncoder
A Variational Autoencoder for face image generation implemented with PyTorch.
This VAE has been trained on a small dataset as the main interest was to implement a first operationnal VAE.
## The dataset
For this kind of application we dont need to have specific name for each picture so the main issue is to collect picture and the best way is of course Google Images.
So thinks to a very usefull Plug-in " I'm a Gentleman " I was able to gather different pictures and build my dataset. I resize and grayscaled them in order to make it quicker. 
## The aim
Just to clarify again i'm not expecting outstanding average loss which would mean perfect reconstruction. That's why i only train it on 100 Epochs.
## The Loss function 
The loss function used here is a combination of the binary cross Entropy and Kullback-Leibler divergence with a factor \Beta that allows disentanglement for values >>1
## Results
![sample_73](https://user-images.githubusercontent.com/45148200/49483519-c2cc7580-f833-11e8-87f8-9241b803f1c2.png)

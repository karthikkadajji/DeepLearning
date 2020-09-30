The notebook contains ways to train an autoencoder. The main idea is to have a convolution and deconvolution to reconstruct the images. The autoencoders are one of the ways which could be used to extract the latent data . 

Train an autoencoder in different ways!!.

Train autoencoder – freeze encoder – train classifier on top
Train autoencoder – train classifier on top of encoder. Do not freeze the encoder, i.e. the encoder is “fine-tuned” on the labeled subset of data as well.
Train a classifier directly on the labeled subset; no pretraining. For fairness, it should have the same architecture as the encoder + classifier above.

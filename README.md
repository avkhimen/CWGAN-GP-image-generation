# Conditional Wasserstein GAN for Synthetic Image Generation

Conditional Wasserstein GAN with gradient penalty for the generation of synthetic images.

## Description

MNIST dataset was used to train the conditional WGAN. Gradient Penalty was also implemented. 

Run the cells in sequence in `cwgan-gp.ipynb` jupyter notebook. Final cell contains code to create synthetic 
image conditioned on a label.

Code in part based on:

* https://keras.io/examples/generative/conditional_gan/
* https://keras.io/examples/generative/wgan_gp/
* https://keras.io/examples/generative/dcgan_overriding_train_step/

## Getting Started

### Dependencies

* tensorflow
* numpy
* matplotlib

See `requirements.txt` file.


## License

Free to use for any purpose
## DCGAN Dog Image Generation
This is a Generative Adversarial Network using DCGAN architecture.

## Data
The data is from Kaggle GAN competition. https://www.kaggle.com/competitions/generative-dog-images/overview
## Model Description:

### Generator
#### Model type:
Convolutional neural network
#### Model usage:
This model generates synthetic images by translating random noise into image-like structures.

#### Architecture:
The model architecture is built using transposed convolutional layers, batch normalization layers, and ReLU activation layers. 

### Discriminator
#### Model type:
Convolutional neural network

#### Model usage:
This model classifies images as real or fake.

#### Architecture:
The model architecture is built using convolutional layers, batch normalization layers, and LeakyReLU activation layers
### Training Details
Loss Function: Binary Cross Entropy for experiment 1 and Relativistic Loss for experiment 2<br>
Optimizer: Adam (learning rate: 0.001)<br>
Batch Size: Configurable<br>
Number of Epochs: 100 (configurable)<br>

### References
https://www.kaggle.com/competitions/generative-dog-images/overview <br>
https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html
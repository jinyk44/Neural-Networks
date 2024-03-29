# Hopfield Network and Feedforward Neural Network
## Introduction
This project was done in  April 2019 as one of the course projects in PHYS498 taught by [Prof. Bryan K Clark](https://physics.illinois.edu/people/directory/profile/bkclark) during my study at University of Illinois at Urbana-Champaign. This project served as an introduction to the world of neural network to physics students. We were taught with the basics of Hopfield Network and Artificial Neural Network and then implemented these two algorithm from scratch. We first used the Hopfield Network recovered a 64x64 grayscale image with half of the pixels corrupted. Then we used Feedforward Neural Network to predict the atomic spins of Ising model.
## Hopfield Network
Hopfield Network was invented in 1982 by J.J.Hopfield. A more general introduction on the this algorithm can be found here [Hopfield Networks are useless. Here’s why you should learn them.](https://towardsdatascience.com/hopfield-networks-are-useless-heres-why-you-should-learn-them-f0930ebeadcd). 
After building the Hopfield Network, we let it memorized some simple images and corrupted some of the pixels and tested the performance of the Hopfield Network. 
Then I let the model memorized a 64x64 grayscale image and corrupted half of the pixels. After a few iterations, it converged to original image with only few pixels corrupted.
<p align = "center">
  <img src = "https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/0.jpg" alt = "0">
  <img src = "https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/1.jpg" alt = "1">
  <img src = "https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/2.jpg" alt = "2">
  <img src = "https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/3.jpg" alt = "3">
  <img src = "https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/4.jpg" alt = "4">
  <img src = "https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/5.jpg" alt = "5">
</p>
<p align = "center">
  Snapshots taken during iterations
</p>

## Neural Network
In building the neural network project, we start-off with simple perceptron and move on to a scalable multi-layer feedforward neural network. I found this [tutorial](https://nndl.github.io/) extremely helpful while implementing my own FNN model. 
After implementing the basics of the model, we were given a dataset that contains all the possible combinations of atomic spins (features) of a 10x10 [Ising model](https://en.wikipedia.org/wiki/Ising_model)and labels of the Ising model. I trained the model on the training set and then tested on the validation set and achieved 91% accuracy. Using the predicated labels on the validation set, I also successfully identified the phase transition of the Ising model.

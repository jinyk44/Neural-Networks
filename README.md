# Hopfield Network and Feedforward Neural Network
## Introduction
This project was done in  April 2019 as one of the course projects in PHYS498 taught by [Prof. Bryan K Clark](https://physics.illinois.edu/people/directory/profile/bkclark) during my study at University of Illinois at Urbana-Champaign. This project served as an introduction to the world of neural network to physics students. We were taught with the basics of Hopfield Network and Artificial Neural Network and then implemented these two algorithm from scratch. We first used the Hopfield Network recovered a 64x64 grayscale image with half of the pixels corrupted. Then we used Feedforward Neural Network to predict the atomic spins of Ising model.
## Hopfield Network
Hopfield Network was invented in 1982 by J.J.Hopfield. A more general introduction on the this algorithm can be found here [Hopfield Networks are useless. Here’s why you should learn them.](https://towardsdatascience.com/hopfield-networks-are-useless-heres-why-you-should-learn-them-f0930ebeadcd). 
After building the Hopfield Network, we let it memorized some simple images and corrupted some of the pixels and tested the performance of the Hopfield Network. 
Then I let the model memorized a 64x64 grayscale image and corrupted half of the pixels. After a few iterations, it converged to original image with only few pixels corrupted.
<p align = “center”>
  <img src=“[Neural-Networks/0.jpg at master · jinyk44/Neural-Networks · GitHub](https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/0.jpg)”  />
  <img src=“/[Neural-Networks/1.jpg at master · jinyk44/Neural-Networks · GitHub](https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/1.jpg)” /> 
  <img src=“[Neural-Networks/2.jpg at master · jinyk44/Neural-Networks · GitHub](https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/2.jpg)  />
  <img src=“[Neural-Networks/3.jpg at master · jinyk44/Neural-Networks · GitHub](https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/3.jpg)”>
   <img src=“[Neural-Networks/5.jpg at master · jinyk44/Neural-Networks · GitHub](https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/5.jpg)”>
   <img src=“”[Neural-Networks/6.jpg at master · jinyk44/Neural-Networks · GitHub](https://github.com/jinyk44/Neural-Networks/blob/master/thumbnail_train/imgs/6.jpg)>
</p>



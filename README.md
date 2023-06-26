# Project 2 - UNC Building Recognition

## About

For our project, we aimed to create a model that is able to identify buildings on campus based on a picture. The model uses a tuned pre-trained ResNet50 Architecture with the last fully connected layer trained with
our dataset containing pictures of UNCC campus build
ings. In order to measure the performance of our model
we used a cross-entropy loss for multiclass image classification. While all loss functions penalize accuracy measurements for incorrect predictions, when using Cross-Entropy,
the accuracy is penalized greatly when confidence is high
but the prediction is incorrect. Thus, we believed this to
be the best way to measure our model’s loss. With regard to
Hyperparameters, they varied during experimentation but for
the final model we utilized a learning rate of 0.0001, batch
size of 32, and a number of epochs equal to 15. The use of
this model led to an accuracy of 86% when tested.

## The Dataset

The dataset of 2700+ images can be found here: https://drive.google.com/file/d/1vNNFWpEnCnzSgFTPbr88ASea69R4NGTY/view?usp=sharing
Please put this folder in a folder titled "4152_Building_Pictures" in the same directory as the notebook.

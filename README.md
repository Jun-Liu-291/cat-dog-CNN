# cat-dog-CNN
Try to build a simple CNN model to classify cats and dogs

## Introduction

Build 4-layers and 5-layers CNN model with fully connected layers to practice on tuning hyperparameters, which are learning rate, batch size, and dropout rate

### cat&dog-v1.ipython 
  training a 4-layers Conv2D model with 0.5 dropout rate. finally get the 83% accuracy in validation set.<br>
  
### cat&dog-v2-findbestLR..ipynb 
  use LearningRateScheduler command to find the best start learning rate

### cat&dog_v3_batchsize.ipynb
  try different batch size to see which is the best choice.
  
### cat&dog_v4_dropout.ipynb
  try different dropout rate to see which choice can solve the overfitting problem and also make the training procedure quick
  
### cat&dog_v5_regularzation.ipynb
  train the model with kernel/bias/activity regularizer but noe dropout, to see the effect.
  
### cat&dog_v6_final
  train a 5-layers CNN model with 2 fully connected layers with 1024 parameters, finally got 84.8% accuracy on test set

### cat&dog_v7_VGG16_pretrain_featrue_extraction.ipynb
  apply trainsfer learning to cats&dogs small dataset
  
### cat&dog-v8-f.ipynb
  train a 6-layers-CNN model with 2 fully connected layers with 1024 parameters on original cats&dogs dataset with 20000 images in training set, finally got 96% accuracy on test set
  
### cat&dog-v9-f.ipynb
  train a 5-layers-CNN model with 2 fully connected layers with 1024 parameters on original cats&dogs dataset with 20000 images in training set, finally got 95.1% accuracy on test set
  

  

# Depth-Estimation-Model
This model was created to predict the depth of a single RGB image of food after transfering a depth model that had been used to predict the depths of indoor scenes, to predict the depth of food images. 
## Idea
Our idea is to use our small [dataset](https://github.com/mhmedwagih1324/Dataset-Creation) to create a model that predicts the depth of a food image starting from the [pretrained Tensorflow weights](http://campar.in.tum.de/files/rupprecht/depthpred/NYU_ResNet-UpProj.npy).

## Content
Some codes of this repository are already implemented in [this repositoy](https://github.com/XPFly1989/FCRN)
## Method
To start training, please follow the following steps:

1. open the [depth_train_code.ipynb](https://github.com/mhmedwagih1324/Depth-Estimation-Model/blob/master/Depth_train_code.ipynb) on [Google colab](https://colab.research.google.com/)
2. run all the cells till the cell that starts training, these cells should import the required libraries, clone this repository and download the required model and dataset.
3. run the cell that starts training the model.
4. run the cell that starts testing the model.
5. the output images of training and testing should appear in the same directory that contains this cloned repository

## Results
Our training & testing results are in the excel sheet [Depth_training_results.xlsx](https://github.com/mhmedwagih1324/Depth-Estimation-Model/blob/master/Depth_training_results.xlsx)
Also some of the output images of train and tests appear in the folder [Training out images](https://github.com/mhmedwagih1324/Depth-Estimation-Model/tree/master/Training%20out%20images)
![train results](train%20results.png)

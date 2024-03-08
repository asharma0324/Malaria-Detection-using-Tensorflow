# Malaria-Detection-using-Tensorflow

I am using the TensorFlow dataset 'malaria' for this project. 

In this project, I have developed a CNN Model for predicting whether a cell image is positive or negative for Malaria.

This image is for an infected cell.

![image](https://github.com/asharma0324/Malaria-Detection-using-Tensorflow/assets/162019532/19f75089-a3ae-4fa3-9dee-cd3d36614f43)

This image is for an uninfected cell.

![image](https://github.com/asharma0324/Malaria-Detection-using-Tensorflow/assets/162019532/c3230623-e633-41c4-8483-8683088b58dd)


I have also used Data Augmentation like 'flip_left_right', 'adjust_saturation', 'Resizing', and 'Rescaling' to increase my model's accuracy.

I have also plotted the confusion matrix assuming a specific threshold. The threshold can be changed depending on whether we require more false negatives or positives.


0.8 is randomly chosen as the threshold set for the confidence value. A more calculated value can be chosen from the ROC plot.

![image](https://github.com/asharma0324/Malaria-Detection-using-Tensorflow/assets/162019532/55b16839-ebbe-4add-a05d-f91319979714)

![image](https://github.com/asharma0324/Malaria-Detection-using-Tensorflow/assets/162019532/66c27774-f7a0-4dec-a6de-2d68be57428b)



In the end, using Tensorboard, I performed HyperParameterTuning to find better parameters for the CNN Model.

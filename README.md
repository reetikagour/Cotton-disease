# Cotton-disease
Crop diseases are an important problem, as they cause serious reduction in quantity as well as quality of agriculture products.
Detection of plant disease through some automatic technique is beneficial as it reduces a large work of monitoring in big farms of crops. Automatic identification and classification of plant diseases can be supportive to agriculture yield maximization.

We have dataset of cotton plants which has four types of images "diseased cotton leaf", diseased cotton plant", fresh cotton leaf", freash cotton plant".

Created deep learning model convolutional neural network(CNN) using keras library for the project cotton disease prediction . CNN is a specialized deep neural network model for handling image data. I have used pre-trained vgg16 model and applied transfer learning. Remooved top three layers from vgg16 and freezed rest of the layers and then added 2 dense layers alond with dropouts and activation funtion is "relu".In the last layer added "softmax" function as it is a multiclass classification problem. The loss function used was “categorical_crossentropy” and the optimizer used was “Adam”. 

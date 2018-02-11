# Handwritten-Digit-Recognition-With-Deep-Learning

This Python project Recognizes Handwritten digits using Artificial Neural Network

Requirements : Python 3.5,sklearn,opencv,numpy,imutils

> train.py file is used for training the model

> test.py file is used for Testing the model on test dataset,It picks up the model from model.pkl file

> model.pkl file is our trained Neural Network

> test_on_image.py file is used to test our ANN model on actual images

> sample_images represent the images on which the model is tested

> One of the Sample Image is as follows:

![alt text](https://github.com/AzharMithani/Handwritten-Digit-Recognition-With-Deep-Learning/blob/master/sample_image.jpg)

> Recognized digits are as Follows:

![alt text](https://github.com/AzharMithani/Handwritten-Digit-Recognition-With-Deep-Learning/blob/master/result2.jpg)

>Another sample image is ,

![alt text](https://github.com/AzharMithani/Handwritten-Digit-Recognition-With-Deep-Learning/blob/master/sample_image2.jpg)

>Its result is:

![alt text](https://github.com/AzharMithani/Handwritten-Digit-Recognition-With-Deep-Learning/blob/master/result1.jpg)


> As we can see in above image ,two of our digits gets classified incorrectly!

> One of the key thing to remember here is that extracting digit area from the natural image requires thresholding
	which is ofcourse in some cases leads to error,hence testing images should have proper exposure and evenly 
	distributed brightness


# Real-time-handwritten-digits-recognition-using-Convolutional-Neural-Network

# Description
Reading handwritten information like examination answer sheets is still a difficult task for many of us, because each one of us is having a different interpretation style. As the world is moving towards digitization, converting the hand written information to a readable digital format reduces the difficulty. This approach will be beneficial for the readers as it gives a better understanding of the information. With the help of machine learning and deep learning algorithms, the hand written patterns can be recognized and classify them accordingly to a digital format with human level accuracy.

This repository deals with predicting the real time handwritten digits only. To classify the handwritten digits MNIST data set is used for training the model. OpenCV python library is used for detecting the patterns in the real time handwritten digits. These detected patterns are predicted to human level accuracy with the help of a Convolutional Neural Network model.

# Environment
* Colab
* Tensorflow
* Keras
* Numpy
* Pandas
* Matplotlib
* Sklearn
* Seaborn
* OpenCV

# Data set
The MNIST data set (Modified National Institute of Standards and Technology database) has 70,000 handwritten images, which is divided into training data set of 60,000 images, and a testing data set of 10,000 images. Each digit in the data set is normalized and centered in a gray-level image with size 28 * 28, or with 784 pixels. All the pixels are stored in csv files, training files has 60,000 rows * 785 columns and testing files has 10,000 rows * 785 columns.
![Dataset](https://user-images.githubusercontent.com/83408384/116879880-dcf62200-ac3e-11eb-8a89-2c1d77f665a2.png)
Sample images from MNIST data set

# Convolutional Neural Network Model 
![Diagram](https://user-images.githubusercontent.com/83408384/116879811-c51e9e00-ac3e-11eb-8397-f2f37c774aad.png)
	Layers
  
CL1 -	Convolutional Layer 1
ML1	- Max Pooling Layer 1
CL2	- Convolutional Layer 2
ML2	- Max Pooling Layer 2
CL3	- Convolutional Layer 3
FL1	- Dropout & Flatten Layer 1
DL1	- Dense Layer 1
DL2	- Dense Layer 2


# Output
![Capture](https://user-images.githubusercontent.com/83408384/116871250-9d750900-ac31-11eb-8293-dbf662b2cc66.PNG)

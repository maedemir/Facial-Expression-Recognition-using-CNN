this is a simple project for facial expression recognition using CNN and FER13 dataset
# Methodology
The convolution operation allows us to save on computation while working with images without compromising on the system’s accuracy. Like MLP, it uses pixel values to build a facial expression recognition system.
In this project I used the Convolutional Neural Networks, to work on the Face expression recognition problem.

# Dataset:
The dataset I used in this face recognition project is the one on Kaggle for the [Facial Expression Recognition Challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
It has face images for seven emotions: anger, disgust, fear, happy, sad, surprise, and neutral of pixel size 48x48. The test dataset has 28,709 samples, and the training dataset has 3,589 samples. There are two columns in the dataset, “emotion” and “pixels.” The emotions have been represented using a number from 0-6 where 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral. The pixel column contains a string of numbers that represent the image.
Here is the the overal CNN architecture used in this project:

# CNN architecture
A CNN architecture primarily involves three types of layers:
### Convolutional layer
### Pooling Layer
### Fully connected layer
I applied batch-normalization after each convolution layer and a dropout layer after each max-pooling layer.

you can see the overl structure of our CNN model below:
![image](https://user-images.githubusercontent.com/72692826/178096520-478a9ef2-60ea-48bc-8929-81688a295b37.png)

# Results
I get the result of 65% accuracy for train data and 60% accuracy for the test data. 

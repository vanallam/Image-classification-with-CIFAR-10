# Image-classification-with-CIFAR-10

I built an image classification model from scratch and trained it by CIFAR-10 dataset, I worked on Google Colab platform to train the model

# The model

the model consists of 5 Conv2D layers and 3 Dense layers the activation of the last Dense layers is softmax activation function

# Trainig

The CIFAR-10 dataset consists of 50000 32x32 colour images in 10 classes as a training data, I split this data to training data and validation data.
I used data augmentation to prevent the model from overfitting. After training for 50 epochs the model achieved 80% accuracy for training data after data 
augmentation.
![loss](https://user-images.githubusercontent.com/56890190/201549604-306ab94a-fe0b-4648-a6df-c37630f3d16b.png)
![acc](https://user-images.githubusercontent.com/56890190/201549620-8bdc4bf5-aa6b-451e-8787-389d3aa8b8e7.png)

# Evaluation

However the training accuracy is 80%, the model accuracy for testing data is 96%. These results are unreasonable at normal conditions but maybe this happened because the model was trained by augmented data and testing data wasn't augmented so maybe the model was extremely generalized

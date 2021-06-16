# Mask-Detection
Real time face-mask detection using Deep Learning and OpenCV

# About Project
This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks.I have used the concept of Transfer learning which required pre-trained model so, in this project I have used MobileNet convolutional neural network.In this pre-trained model does not contain our images so we have to provide our own images to predict our faces.The CNN manages to get an accuracy of 99.1% on the training set and 98.72% on the test set after that we eill save the model and Then stored weights of this CNN Model are used to classify as mask or no mask in real time using OpenCV. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

# Working

with mask
![with_mask](https://user-images.githubusercontent.com/64475805/122226087-3f477100-ced3-11eb-8a1a-6a0722a7fa54.jpg)

without mask
![without_mask](https://user-images.githubusercontent.com/64475805/122226184-58e8b880-ced3-11eb-8d54-d108b24f8ad1.jpg)




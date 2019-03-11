# Face-Recognition

This project is applying deep neural network for face recognition problem.

Main steps are:

1. Captured pictures from a video using FPS of 30, then applied Dlib (sliding window) to detect face within the picture
2. Applied Caffe to train deep neural network to get models based on AlexNet and GoogleNet
3. Feature Extraction for gallery set and probe data (CNN forwarding, using feature layer)
4. Matching by computing the distances between the probe feature with all the features in gallery
5. Conduct Fine-tuning on pre-trained model for face gender classification (change last layer(s))

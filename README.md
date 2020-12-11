# PPL_Project
#Topic : - Sign Language Detection using machine learning

#Overview 
This is a Machine Learning Project based on Convolutional Neural Networks (CNN)
Our project can detect hand gestures based on the American Sign Language. We also have added 
the feature of creating our own customized gestures for integrating with some other application.

Technique Used --> Deep Learning and Machine Learning
Type of Neural Network --> 3 layered Convolutional Neural Network
Programming Language  --> Python
Modules Used --> Keras and Tensorflow for training the model.
                  OpenCV for Image processing

# Basic Workflow 

1) Creating Gestures
2) Image Extraction and training the model
3) Testing the model and displaying the results.
 
 
 # Sequence of executing the code 
 
 Creating the gestures and then training the model --> Done by cnn_keras.py
                                                        It trains the model using a 3 layered CNN
 
 Testing and displaying the result :--->
      1) set_hand_hist.py - Setting the right lighting conditions for proper detection of signs.
      2) recognise_gestures.py - Predicts the sign using the trained CNN model.
      3) fun_util.py - Display the predicted sign on the window.
      
      
      
 Submitted By -->
 1) Atharva S Marathe 
 2) Avishkar Andhale 
 3) Darshan Shah
 

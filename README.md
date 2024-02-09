# Action Detection for Sign Language

This notebook demonstrates an end-to-end workflow for sign language action detection using computer vision and deep learning.

## How it works

The key steps in the tutorial are:

1. Install and Import Dependencies - Setting up the necessary Python libraries

2. Detect Face, Hand and Pose Landmarks - Using mediapipe to detect keypoints from video frames 

3. Extract Keypoints - Retrieving the (x, y) coordinates of the detected keypoints

4. Setup Folders for Data Collection - Creating directories to store training data

5. Collect Keypoint Sequences - Capturing video frames and saving keypoint coordinate sequences 

6. Preprocess Data and Create Labels - Encoding the sequences, standardizing data and generating one-hot labels

7. Build and Train an LSTM Deep Learning Model - Developing and training an LSTM network for classification

8. Make Sign Language Predictions - Using the trained model to predict actions on new data

9. Save Model Weights - Storing the trained model parameters 

10. Evaluation using a Confusion Matrix - Analyzing model performance with a confusion matrix

11. Test in Real Time - Demonstrating real-time prediction on live video input

By walking through these steps, the notebook provides an end-to-end demonstration of developing a deep learning model for sign language action detection from video sequences.

## Libraries
* tensorflow
* opencv-python
* mediapipe
* scikit-learn
* matplotlib
## Usage 
If you want to train the model on your data, you can either do it using the live feed and performing an action 30 times or you can use data such as INCLUDE (AI4Barath) to train on video data just by doing tiny changes in the open-cv code

Once done you can save your model and create your own instance!

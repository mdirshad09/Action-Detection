# Action-Detection
The aim of this project is to develop a system that can recognize specific actions using a camera. The project involves several steps:

Dataset creation: A dataset is created that includes videos of three actions: 'hello', 'iloveyou', and 'thanks'. This dataset serves as the training data for the model.

Feature extraction: The project uses Mediapipe, a library for real-time perception, to extract holistic features from the videos. These features capture the key points and movements of the human body, which are relevant for action recognition.

LSTM model training: The project utilizes a Long Short-Term Memory (LSTM) model, which is a type of recurrent neural network (RNN), to learn patterns from the extracted features. The LSTM model is trained on the dataset, using the extracted features as input, to learn how to recognize the three actions.

Real-time action recognition: Once the LSTM model is trained, it is capable of recognizing the actions in real-time. The model takes the live camera feed as input, extracts holistic features from the video frames in real-time using Mediapipe, and uses the trained LSTM model to classify the actions as 'hello', 'iloveyou', or 'thanks'.

The ultimate goal of the project is to develop a system that can accurately and reliably recognize specific actions in real-time using a camera, which could have various applications such as gesture recognition, human-computer interaction, or activity monitoring.

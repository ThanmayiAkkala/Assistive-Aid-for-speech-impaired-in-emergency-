# Assistive-Aid-for-speech-impaired-in-emergency-
Sign language is used to convey feelings and thoughts as well as
reinforce information given in everyday discussions. Speech-impaired
people use sign language as a means of communication to help
themselves interact with others. Several studies using deep learning were
made to bridge the communication gap between normal and speech-
impaired people. This project takes the effort to detect the gestures that
are indicating medical emergencies, situations like accident, fire, and
serious health issues, by recognizing the signs and displaying the result
as text data. The system uses OpenCV to get a live video feed as input
and uses the MediaPipe Hand Estimation model to extract relevant
features from the video samples. The extracted features are passed
through a custom-trained machine learning model to classify each input
video frame into accurate text data. The displayed data can indicate pain,
accident and other gestures using sign language. The proposed system
provides real-time feedback to the user by highlighting the detected
gesture and displaying a corresponding message. The training and
prediction of hand gestures are performed by deep neural network
models, and the performance is measured with LSTM model (Long
Short- Term Memory), dense, and dropout layer models. The results of
the proposed work demonstrate the comparative results in detecting and
recognizing the emergency gestures taken as samples under study, which
gives an accuracy of above 90%. For LSTM and dense model, the system
reports an accuracy over 95% with 30 samples, whereas after adding
dropout ,the accuracy is 94% with 50 samples .Therefore, this project
provides a useful tool to understand the communication of sign language
by common people and aid speech-impaired people in emergency
situations, thereby improving humans’ ability to respond quickly .

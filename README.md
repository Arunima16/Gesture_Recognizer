# Gesture_Recognizer
Gesture_Recognizer enables the ability to interpret and understand human gestures and allows for natural and intuitive communication between humans and machines, enabling more immersive and interactive experiences.
It can also be used for Sign Language Detection. American Sign Language (ASL) is an alternative method used by people who are unable to communicate with others by speech. It consists of a set of gestures wherein every gesture represents one letter, number, or expression.
In this project for Hand Detection purpose, the MediaPipe library is used.
MEDIAPIPE: Finds Hands using the mediapipe library. Exports the landmarks in pixel format. Adds extra functionalities like finding how many fingers are up or the distance between two fingers. Also provides bounding box info of the hand found.
This project is made using Python language.
Data Collection: Gathered a diverse dataset comprising a variety of static hand gestures and American Sign Language (ASL) symbols in 11 different classes each having 300 sample images ensuring variations in hand orientations to enhance the system’s robustness.
Training of collected data:  To train the model from the collected sample data we used “Google Teachable Machine”  We created 11 different classes of gestures and uploaded the corresponding collected sample images for each class. Then we trained the model for these 11 classes. We created the trained model using tensorflow and keras and used it in our project.
Developed Gesture_Recognizer based on Computer Vision techniques achieves accurate and real-time recognition of those predefined hand gestures for which data is collected.
You can furthermore collect sample images for your choice of gestures and again train the model for all the classes of the collected dataset and use that trained model in the project for classification in real-time.




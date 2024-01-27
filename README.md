# Real-Time-Emotion-Recognition

The emotion recognition model, trained on the FER-2013 dataset, achieves an exceptional accuracy of over **95%** by employing an increased number of epochs during training (beyond the provided code snippet). 

This dataset, consisting of 28,709 examples in the training set and 3,589 examples in the public test set, enhances model diversity and generalization, ensuring precise classification of seven emotions: 

**0 = Angry**

**1 = Disgust**

**2 = Fear**

**3 = Happy**

**4 = Sad**

**5 = Surprise**

**6 = Neutral**


The project utilizes a deep learning model based on **transfer learning**, specifically the **MobileNetV2** architecture, to classify facial expressions into seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral. The training dataset comprises facial images from diverse individuals, resized to 224x224 pixels.

The project demonstrates live emotion recognition through **webcam** input, utilizing a pre-trained deep learning model. The system detects faces in the live feed using Haar cascades, extracts facial regions, and feeds them into the trained model for emotion prediction. The recognized emotion is then overlaid on the video stream, providing real-time feedback.

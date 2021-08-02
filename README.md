# HackerEarth-TomNJerry_EmotionDetection_DeepLearning
**Model that detects the emotions of Tom or Jerry in each video frame.**
***
![enter image description here](https://github.com/Qadir92/HackerEarth-TomNJerry_EmotionDetection_ImageClassification/blob/main/Prediction%20Score.png?raw=true)
***

Download the dataset [here](https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-emotion-detection-tom-jerry-cartoon/)
***
**Steps in the notebook:**
 1. Loading the data into colab notebook.
 2. Frames extraction from the train video.
 3. Center Crop the frames in 500x720 size and resize into 224x224 for best predictions results.
 4. Build a convolution2d model with 3 layers and fit Train images with *Adam* optimizer and *f1* metrics.
 5. Extract the frames from the test video and repeat step 3.
 6. Make the predictions using the deep learning model.
 ***
 **Observation**: Accuracy of the model can be improved if longer train videos are fit to the model.
***
To check out my notebook, please click [here](https://github.com/Qadir92/HackerEarth-TomNJerry_EmotionDetection_ImageClassification/blob/main/Tom_Jerry.ipynb)

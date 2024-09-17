# Real-Time-Human-Gym-Pose-Detection-With-AI
The "Real-Time Human Gym Pose Detection" is an innovative project that combines fitness tracking with artificial intelligence. The primary focus of this project is to enhance workout experience by utilizing multiple models including CNN Time Distributed (LRCN), LSTM and 3-D CNN to classify types of exercise and apply it to real time application while allowing the users to count repetitions of the exercise. For our validation part, we are using YOLO and MediaPipe to draw the bounding box on the video file before running the classification.
Please follow the following order to view files

1. **File_1_GoodModels:** this file consist of 2 models which are giving high accuracy and also consists of all the methods used to create the models

2. **File_2_ConvoLSTM:** this file contains convolstm model (3rd model)

3. **File_3_RealtimeFeed:** this file consists of the saved model's integration with the real time feed.

4. **cnn3d1.0.h5:** this is the .h5 file of the model with highest accuracy. it has been created by the model present in  File_1_GoodModels and used in File_3_RealtimeFeed for real time detection

5. **Media1:** is the recorded output of the project

6. The datasets have been provided as a link in the email

7. The link for data set: https://paperswithcode.com/dataset/infiniterep 

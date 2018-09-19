# simpsons-facial-recognition
Mod 4 Project: Creating Network to Identify Simpson Characters

Object Detection:
All Object Detection work was done following a great step by step tutorial by sentdex. It utilizes the Tensorflow Object Detection repo and the SSD MobileNet Architecture trained on annotated images of Bart Simpson. 
Tensor Flow Object Detection Repo: https://github.com/tensorflow/models/tree/master/research/object_detection
SentDex Tutorial Part 1: https://www.youtube.com/watch?v=COlbP62-B-U&vl=en

The below video was created to attempt to apply SSD MobileNet to a Simpsons video clip to identify Bart Simpson. 
https://www.youtube.com/watch?v=531vqD6egMs&feature=youtu.be

Results were less than stellar due to an underfit model and the training set was only trained on one class (Bart Simpson). However, this was a great learning experience to get familiar with transfer learning and working with object detection architectures. Additionally, we were able to apply OpenCv to break down a video and apply the object detection model to each frame. We were also able to use OpenCV to recompile the the new frames into a video. 

Next steps:
1. Add other characters to training set so the model does not think every Simpsons character is Bart Simpson. 
2. Retrain model- we only got 50 epochs into training the SSD Mobile Net on a CPU before the laptop crashed, therefore the model is underfit.





# Object_Detection

Uses Keras

Based on:
https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/
https://github.com/experiencor/keras-yolo3

yolov3_original.py
Original DarkNet code. WeightReader class used by implement.py

yolov3_implement.py
Creates model with weight file. Most classes needed from original are copy and pasted into this file. Some are amended.

yolov3_predict.py uses model, draws boxes over image. Amended for persons detected only

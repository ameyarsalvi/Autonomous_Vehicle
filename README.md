# Autonomous_Vehicle

## Finding Lanes:
The finding lanes algorithm helps in lane detection both real time and from provided videos. The lane detection algorithm is developded for detection the sharpe changes in the pixel intensities to detect the lanes and then is optimized for less memory usage and smoothened using Hough Transforms.
![Lane Detection](https://github.com/ameyarsalvi/Autonomous_Vehicle/blob/master/LaneDetect.JPG)

## Traffic Signs Identification:
The traffic signs algorithm has been designed using the LeNet model for Convoluted Deep Neural Network do identify between 43 different classes of traffic symbols. The model has been paramatrized for upto 98% of training and validation accuracy and upto 96% of test accuracy.

Accuracy Convergence:
![Accuracy](https://github.com/ameyarsalvi/Autonomous_Vehicle/blob/master/Accuracy_TS.JPG)

Results:
![Image Classes](https://github.com/ameyarsalvi/Autonomous_Vehicle/blob/master/TS.JPG) ![Prediction](https://github.com/ameyarsalvi/Autonomous_Vehicle/blob/master/TSid.JPG)

## Motion Control:
This project involves performing behaviour cloning for an autonomous vehicle simulator. The Unity simular was used for simulation and testing. The NVIDIA's convolutional model was used for this. The car was designed for self steering and throttle control in untrained environment. 

![Behaviour Cloning](https://github.com/ameyarsalvi/Autonomous_Vehicle/blob/master/SelfDrive.JPG)

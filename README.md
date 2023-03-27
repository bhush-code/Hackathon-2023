# Drowsiness Detection OpenCV 😴 🚫 🚗
This code can detect your eyes and alert when the user is drows.
## Applications 🎯
This can be used by Drivers who tend to drive for a longer period of time that may lead to accidents.
### Code Requirements 🦄
The example code is in Python ([version 3.6](https://www.python.org/download/releases/3.6/))
### Dependencies
1) import cv2
2) import imutils
3) import dlib
4) import time
5) import numpy
6) imoprt twilio



### Description 📌

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm and sends sms to the Emergency contact if the driver appears to be drowsy.

### Algorithm 👨‍🔬

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It checks 15 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.
#### Relationship
<img src="https://github.com/bhush-code/Hackathon-2023/blob/api/Assets/eye2.png">


#### Summing up

<img src="https://github.com/bhush-code/Hackathon-2023/blob/api/Assets/eye3.jpg">

### Execution 🐉
To run the code, type `python Drowsiness_Detection.py`

```
python Drowsiness_Detection.py
```

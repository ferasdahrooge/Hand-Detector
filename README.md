# Hand-Detector

Using MediaPipe to detect both hands as well as the label of each hand , the angle for every finger in comparison to the x-axis

Steps to consider:

## Install / Import Libraries

#### installation

`!pip install mediapipe opencv-python`

#### importing

`import mediapipe as mp`
`import cv2`
`import numpy as np`
`import uuid`
`import os`
`import matplotlib.pyplot as plt`

## Code

And then Run Code Starting with
`mp_drawing = mp.solutions.drawing_utils`
`mp_hands = mp.solutions.hands`

### for Hand Detection

A screenshot Demonstrating the hand Detection

![HandDetected](<Output\ Images/hand-detector.jpg>)

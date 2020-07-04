# Introduction 

In this project, we blur a person's face from either a live video stream or a picture. 

## Importing the necessary packages

We first need to import all the necessary packages for our project to work: 

```swift
from pyimagefinder.face_blurring import anonymize_face_pixelate
from pyimagefinder.face_blurring import anonymize_face_simple
from imutils.video import VideoStream
import numpy as np
import argparse
import imutils
import time
import cv2
import os
```


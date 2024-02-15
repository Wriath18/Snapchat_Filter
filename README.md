# Snapchat Filter Project: Sunglasses and Mustache with Haar Cascades

## Description:

This project implements a real-time Snapchat-style filter using OpenCV and Haar cascade classifiers to detect eyes and noses on a webcam feed. It then superimposes sunglasses and a mustache onto the detected features, creating a fun and interactive experience.

## Features:

- Detects eyes and noses using Haar cascade classifiers (`frontalEyes35x16.xml`, `haarcascade_nose.xml`).
- Overlays sunglasses and a mustache PNG image onto the detected features.
- Allows adjustable scaling of the filter elements.
- Transparently blends the filter elements for a natural look.
- Provides error handling and informative messages.

## Setup:

### Dependencies:

- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)

### Haar cascade classifiers:

1. Download `frontalEyes35x16.xml` and `haarcascade_nose.xml` from [OpenCV GitHub](https://github.com/opencv/opencv/tree/master/data/haarcascades).
2. Place them in the same directory as your Python script.

### Sunglasses and Mustache Images:

Save your desired sunglasses and mustache PNG images in the same directory as your script.

# Face recognition
Detect and recognize faces in images.

Full workflow of training model can be found in [face_detection.ipynb](https://github.com/James-Leslie/computer-vision/blob/master/face-recognition/face_detection.ipynb).

Once model is trained, webcam example can be run using `webcam_detection.py`.

## Getting started (on Windows)
Feel free to clone this repository and make a pull request with instructions for other OS's

### 1. Install OpenCV
[PyPi link](https://pypi.org/project/opencv-python/)
```python
pip install opencv-python
```

### 2. Install imutils
[PyPi link](https://pypi.org/project/imutils/)
```python
pip install imutils
```

### 3. Collect images of faces
  1. Create one folder per person we want to be able to recognize.
  2. Add all available images of each person's face to their folder. Make sure there is just one face per image.
  3. Create an "unknown" folder with some images of random people. Make sure there is decent variety in these images.

Folder structure should be as follows (Use the `dataset` subdirectory as an example):
```
dataset
  person1
    1.jpg
    2.jpg
    ...
  person2
    1.jpg
    2.jpg
    ...
  ...
  unknown
    1.jpg
    2.jpg
    ...
```

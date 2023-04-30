# Eye Blink Count Detection

This Python script detects the number of times a person blinks their eyes in a video feed from a camera connected to the computer. It uses the following libraries:

- OpenCV (`cv2`)
- dlib
- scipy.spatial
- imutils.face_utils

## Setup

To run this script, you need to have Python 3 installed on your system. You also need to install the required libraries. You can do this by running the following command in your terminal:

```
pip install opencv-python dlib scipy imutils
```

Note that the `dlib` library requires you to install the C++ library `cmake` on your system first.

## Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the `eyeBlinkCount.py` file.
3. Run the following command in your terminal to start the script:

```
python eyeBlinkCount.py
```

The script will start capturing video from the default camera connected to your system. The number of blinks detected will be displayed in the video feed.

Press 'q' to quit the script.

## Notes

- You can modify the threshold for eye closure detection by changing the value `0.3` on line 23 of the script.
- You can change the path to the `shape_predictor_68_face_landmarks.dat` file on line 10 of the script to the path where the file is located on your system.

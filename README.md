# Real-Time-Colour-Detector-using-HSV-colorspace

This project demonstrates a real-time color detection system utilizing the HSV (Hue, Saturation, Value) colorspace with OpenCV in Python. The application captures video input from a webcam, converts the frame to HSV, and detects specific colors in real-time. A bounding box is drawn around the detected color region in the video feed.

## Features
- Real-Time Video Processing: Capture and process video frames from the webcam in real-time.
- Color Detection in HSV: Convert BGR color values to HSV and define the detection range.
- Bounding Box Display: Draw a bounding box around detected colors, providing a visual indication on the video feed.
- Simple and Efficient: Easy to modify and extend for different colors or detection criteria.

## Requirements
- Python 3.x
- OpenCV (cv2)
- NumPy
- PIL (Python Imaging Library)

## How It Works
- Color Conversion: A specified BGR color is converted to its HSV equivalent to define a range for detection.
- Mask Creation: The video frame is converted to the HSV colorspace, and a mask is generated to isolate the specified color.
- Bounding Box Drawing: If the color is detected within the frame, a bounding box is drawn around the detected area.
- Real-Time Display: The processed frame is displayed in real-time, showing the bounding box around the detected color.

## Customization
- Modify the colour variable to detect different colors by providing the desired BGR value.
- Adjust the HSV range in the get_hsv function to fine-tune color detection sensitivity.

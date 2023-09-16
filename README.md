# Simple Color Detection using OpenCV

## Project Description

This project demonstrates a simple color detection algorithm using OpenCV and Python. When you run the code, it captures video from your webcam or a video file and allows you to interactively select a color to detect. The chosen color is then highlighted in real-time within the video stream.

## How it Works

1. Run the code using the provided script (`color_detection.py`).

2. A video window will appear, showing the input from your webcam or a video file.

3. Click on a color within the video window to select it for detection.

4. The code will identify and highlight pixels of the selected color in real-time with a bounding box.

5. Press the 'q' key to quit the video stream.

## Dependencies

- Python 3.6+
- OpenCV (cv2)
- NumPy

## Usage

1. Clone the repository to your local machine.

2. Install the required dependencies using pip:

   ```bash
   pip install opencv-python numpy

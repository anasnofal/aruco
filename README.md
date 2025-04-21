# ArUco Marker Detection with OpenCV

This project detects ArUco markers from a webcam stream using OpenCV and highlights the marker with ID `27`. If the marker is found, it draws a bounding box, marks the center, and displays the marker's ID on the video feed.

## 📦 Requirements

- Python 3.x
- OpenCV (with ArUco module)
- imutils
- numpy

Install them with:

```bash
pip install opencv-contrib-python imutils numpy

## How to Run
Clone the repo and run the script:

```bash
git clone https://github.com/yourusername/aruco-marker-detection.git
cd aruco-marker-detection
python main.py

# Face Detection using OpenCV

A real-time face detection project built using Python and OpenCV.

This project captures live video from a webcam and detects human faces using the Haar Cascade Classifier.

## Features

- Real-time face detection using webcam
- Face bounding box detection
- Displays "Face Detected" label
- Simple and lightweight implementation

## Technologies Used

- Python
- OpenCV
- Haar Cascade Classifier
- Jupyter Notebook

## How It Works

1. The webcam captures live video.
2. Each video frame is converted into grayscale.
3. OpenCV's Haar Cascade Classifier detects faces.
4. A rectangle is drawn around each detected face.
5. The system displays the "Face Detected" label.

## Installation

Install OpenCV:

```bash
pip install opencv-python==4.10.0.84
```

## How to Run

1. Open `Face_Detection.ipynb` in Jupyter Notebook.
2. Run the notebook cells.
3. Allow webcam access if prompted.
4. Press `Q` to stop the webcam.

## Project Structure

```text
Face-Detection-OpenCV/
│
├── Face_Detection.ipynb
├── README.md
└── requirements.txt
```

## Note

This project uses your computer's local webcam, so it needs to be executed on a local machine. Webcam functionality will not run directly on GitHub.

## Author

Ayush Sharma

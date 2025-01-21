# Face Recognition Project

This project implements a real-time face recognition system using OpenCV, DeepFace, and Python's threading module. The application captures video from the webcam, detects faces, and identifies them using pre-trained models provided by the DeepFace library. Threading is employed to enhance performance by handling face recognition tasks asynchronously.

## Features

- **Real-time Face Detection:** Utilizes [OpenCV](https://opencv.org/) to detect faces in live video streams.
- **Face Recognition:** Employs [DeepFace](https://github.com/serengil/deepface) to recognize detected faces using state-of-the-art models.
- **Multithreading:** Implements threading to perform face recognition tasks concurrently, improving the application's responsiveness.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/face-recognition-project.git
## Project Structure

```css
face-recognition-project/
│
├── reference_images/
│   ├── john_doe.jpg
│   └── jane_smith.jpg
│
├── main.py
├── requirements.txt
└── README.md

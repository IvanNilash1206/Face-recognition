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
   
2. **Navigate to the Project Directory:**

   ```bash
   cd face-recognition-project

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
## Usage
1. **Prepare Reference Images:**
   Place images of individuals you want the system to recognize in a directory named reference_images/. Ensure each image is named with the person's name (e.g., john_doe.jpg).

2.**Run the Application:**
   Execute the main script to start the face recognition system:
   ```bash
   python main.py
   ```

   The application will access your webcam and begin detecting and recognizing faces in real-time. Recognized faces will be labeled with their names on the video feed.
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
```

- reference_images/: Directory containing reference images for known individuals.
- main.py: Main script to run the face recognition application.
- requirements.txt: List of required Python packages.
- README.md: Project documentation.

## Acknowledgments
- **Deepface:** A lightweight face recognition and facial attribute analysis library for Python.
- **OpenCV:** An open-source computer vision library for image and video processing.

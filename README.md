# Title: Real-Time Traffic Vehicle Detection

## Description
This Streamlit application performs real-time vehicle detection in traffic videos. Users can upload a video file, and the application will process it to identify vehicles, draw bounding boxes around them, and display the vehicle count. This project utilizes the YOLOv8 object detection model for accurate and efficient vehicle recognition in video streams.

## Responsibilities
### * Video Upload and Processing: 
Allows users to upload video files in common formats like MP4, AVI, and MOV, and temporarily stores them for processing.
### * Real-time Vehicle Detection: 
Employs the YOLOv8 model to analyze video frames and detect vehicles within them.
### * Visual Output: 
Displays the processed video frames in the Streamlit app, overlaying bounding boxes around detected vehicles and showing a real-time vehicle count.
### * User Interface: 
Provides a user-friendly interface built with Streamlit, including a video uploader and a dynamic display area for the processed video.

## Libraries Used:
### 1.streamlit:
For creating the interactive web application and user interface components.
### 2.cv2 (OpenCV): 
For video processing tasks such as reading video files, frame manipulation, resizing frames, drawing bounding boxes, and adding text overlays.
### 3.torch: 
The core PyTorch library, used as the backend for the YOLOv8 model.
### 4.Ultralytics (YOLO): 
Provides the YOLOv8 object detection model, pre-trained weights, and functionalities for performing object detection.
### 5.tempfile: 
For creating temporary files to store uploaded videos, ensuring efficient handling of video data without permanent storage.
### 6.numpy: 
For numerical operations, especially for handling image and video frame data as arrays.
### 7.io.BytesIO: 
While imported, this library isn't directly used in the provided code snippet. It's typically used for handling in-memory binary streams, which might be relevant for more advanced video processing or handling video data in bytes format, but it's not essential to the core functionality shown.

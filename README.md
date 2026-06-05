# VisionTrack
## Real-Time Object Detection using Webcam and OpenCV

### Project Overview
This project demonstrates real-time object detection using a webcam with OpenCV and a pre-trained deep learning model. The system captures live video frames, detects objects present in each frame, and displays bounding boxes along with object labels and confidence scores.

---

## Technologies Used
- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib
- YOLO Object Detection Model
- Webcam

---

## How It Works

### 1. Initialize Webcam
- Access the system webcam using OpenCV.
- Capture live video frames continuously.

### 2. Load Detection Model
- Load the pre-trained YOLO model.
- Load the class labels used for object recognition.

### 3. Process Video Frames
- Read frames from the webcam.
- Convert each frame into a blob format suitable for the neural network.

### 4. Detect Objects
- Pass the frame through the detection model.
- Identify objects and calculate confidence scores.

### 5. Apply Filtering
- Remove weak detections using a confidence threshold.
- Apply Non-Maximum Suppression (NMS) to avoid duplicate bounding boxes.

### 6. Display Results
- Draw bounding boxes around detected objects.
- Show object names and confidence percentages on the video feed.

### 7. Exit Application
- Press a designated key (e.g., 'Q') to stop detection and close the webcam.

---

## Output

### 🔹 Live Webcam Feed
Real-time video stream captured from the webcam.

### 🔹 Detected Objects
Objects are highlighted with bounding boxes, labels, and confidence scores while the video is running.

---

## Key Concepts Learned
- Real-Time Object Detection
- Webcam Video Processing
- Deep Learning-Based Detection
- Bounding Box Generation
- Confidence Score Evaluation
- Non-Maximum Suppression (NMS)
- OpenCV Video Capture
- Computer Vision Applications

---

## Result
The project successfully performs real-time object detection using a webcam and a pre-trained YOLO model. By processing live video frames and accurately identifying objects, the system demonstrates a practical computer vision application suitable for surveillance, monitoring, and automation tasks.

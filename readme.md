# CodeAlpha_ObjectDetectionTracking

CodeAlpha AI Internship - Task 4: Object Detection and Tracking

This project detects objects in a video using a pre-trained YOLOv8 model and tracks them across frames using ByteTrack (a SORT-family tracker). The output video shows bounding boxes, class labels and tracking IDs.

## How it works
1. Load the video with OpenCV
2. Detect objects in each frame with YOLOv8
3. Draw bounding boxes and labels
4. Track objects with ByteTrack to give each one a persistent ID
5. Save the annotated video

## Output
See `download.mp4` in this repository.

## Run
Open the notebook in Google Colab, upload a video and run the cell.

## Tech
Python, OpenCV, Ultralytics YOLOv8, ByteTrack

# CSGO Player Detector
This is a course project completed with other 2 student
Introduction
This is a computer vision project based on YOLOv11n that automatically detects player characters (CT and T) in the CSGO game. The project supports both still image and real-time video processing, suitable for game analysis and live streaming applications.

Function
- Automatically classify and detect CT and T roles.
- Use data augmentation (such as HSV adjustment, rotation) to improve model robustness.
- Achieve real-time video processing at 50 FPS.

Technology Stack
- **Language**: Python
- **Framework**: PyTorch, Ultralytics YOLO, OpenCV
- **Environment**: Google Colab

Results
- The test set mAP@0.5 reaches 0.877 (CT: 0.920, T: 0.835).
- Video processing speed is about 50 FPS, suitable for real-time applications.

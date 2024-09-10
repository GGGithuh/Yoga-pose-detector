Yoga form classifier using YOLOv8m

This project is a Computer Vision Project using YOLOv8m model for posture analysis, 
to detect if the yoga pose taken by a person is in the correct sequence or not. 
We experimented with MediaPipe too. 

Key Components:
- Model: YOLOv8m for pose detection
- Keypoints: Defined in KEYPOINT_DICT, covering essential joints and body parts,
  for different classes "Good" or "Bad"
- CSV Structure: The script creates columns for tracking
  pose data(x,y coordinates of keypoints for each detected person)
- Video Processing: Processes video frames, extracts keypoints, and stores them in a CSV file

  

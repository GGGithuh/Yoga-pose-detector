Yoga form detector using YOLOv8m

This project is a Computer Vision Project using YOLOv8m model for posture analysis, 
to detect if the yoga pose taken by a person is in the correct sequence or not. 
We experimented with MediaPipe too. 

We have created a Streamlit App with the link: [
](https://yoga-pose-detector.streamlit.app/)

This Streamlit App takes video inputs with a Limit 200MB, mp4,avi,mov,mpeg. 
For live trials, please ensure your right profile faces the camera, with a distance of approximately 10ft and appropriate lighting. 

Key Components:
- Model: YOLOv8m for pose detection
- Keypoints: Defined in KEYPOINT_DICT, covering essential joints and body parts,
  for different classes "Good" or "Bad"
- CSV Structure: The script creates columns for tracking
  pose data(x,y coordinates of keypoints for each detected person)
- Video Processing: Processes video frames, extracts keypoints, and stores them in a CSV file

  

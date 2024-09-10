Yoga form detector using YOLOv8m

This project is a Computer Vision Project using YOLOv8m model for posture analysis, 
to detect if the yoga pose taken by a person is correct or not. 

Problem Statement: 
With the increasing popularity of yoga, many people want to learn and practice it on their own. However there are many versions taught as 'Sun Salutation Type A', 'Sun Salutation Type B', etc which do not do justice to the age old reputation of Surya Namaskar as a complete body workout. We are focusing on the version taught for generations. 

Solution:
Here is an attempt to develop a tool that can help learners identify their pose. 

Impact:


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

  

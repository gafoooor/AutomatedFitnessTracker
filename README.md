# Automated Fitness Tracker Using Computer Vision and Deep Learning  

### Overview

This Python-based fitness application uses **computer vision** and **deep learning** to track human posture during exercises and provide real-time feedback. It utilizes **OpenCV** for image processing and integrates the **OpenPose model** to accurately detect and track body poses. Additionally, it leverages a **VGG architecture** for feature extraction to assist in detecting movement and counting repetitions. 

### Features

- **Real-time posture detection** using OpenPose.
- **Exercise repetition counting** based on pose estimation.
- **Posture feedback** with angle calculation for key joints (e.g., elbows, knees).
- **Visualization of metrics** such as:
  - Number of repetitions completed.
  - Visual feedback on correct or incorrect posture.
  - Real-time angle display during exercises.
  
### Technologies Used

- **Python**
- **OpenCV** - for real-time image and video processing.
- **OpenPose** - for detecting and tracking human body key points.
- **VGG Architecture** - used for feature extraction to improve pose analysis.
- **Matplotlib** - for visualizing angles and repetitions.
- **Numpy** - for efficient numerical computations.

### Usage

- **Run the application using your webcam:**

   ```bash
   python automated curl counter.py

- The system will begin detecting poses in real-time and tracking the exercise you're performing. It will count repetitions, provide visual feedback on posture, and display the angles of key joints.

- Results, including the number of reps and joint angles, will be displayed on the screen in real-time.

### Example Output

During an exercise, the application will show:

- Number of repetitions completed.
- Angle of key joints (like knees, elbows) to ensure proper form.

### Acknowledgments

- OpenCV
- OpenPose
- VGG Architecture

### Output

<img width="314" alt="image" src="https://github.com/user-attachments/assets/67b64ffb-bdbf-49d4-b7b5-72fae531eb89">

<img width="314" alt="{5758D2A9-4F81-488F-AA54-DC994CA8BC56}" src="https://github.com/user-attachments/assets/25f69a24-3aed-40ad-92e7-0fa25522d3a9">



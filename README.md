
*Facial and Hand Landmark Detection*

*This project demonstrates real-time facial and hand landmark detection using the Mediapipe library in Python. The program captures video from the default camera, detects facial landmarks, and overlays them on the video feed. Additionally, it detects and overlays landmarks for both right and left hands.

*Requirements
1. Python 3.x
2. OpenCV (cv2)
3. Mediapipe

*Installation
You can install the required libraries using pip:

pip install opencv-python
pip install mediapipe


*Usage
1. Run the script.
2. Position yourself in front of the camera.
3. Facial and hand landmarks will be detected and displayed in real-time.


*Description
1. The program initializes the Holistic model from the Mediapipe library with specified minimum detection and tracking confidences.
2. It captures video from the default camera (0).
3. The frame is resized for better visualization.
4. The frame is converted from BGR to RGB for Mediapipe processing.
5. Facial landmarks are detected and drawn on the frame.
6. Hand landmarks for both right and left hands are detected and drawn on the frame.
7. The frame is flipped horizontally to prevent the mirrored effect.
8. Frames per second (FPS) are calculated and displayed on the video feed.
9. Press 'q' to exit the program.


*Code Structure
1. Import Libraries: Import necessary libraries including OpenCV, Mediapipe, and time.
2. Initialize Holistic Model: Initialize the Holistic model from Mediapipe.
3. Capture Video: Connect to the default camera and capture frames.
4. Process Frames: Convert frames to RGB, process them using the Holistic model, and draw landmarks on the frames.
5. Display FPS: Calculate and display FPS on the video feed.
6. Exit Condition: Break the loop when 'q' is pressed.
7. Access Landmarks: Demonstrate accessing hand landmarks in the Holistic model.
8. Release Resources: Release the camera and destroy all windows when done.

# Rep Counter using Mediapipe and OpenCV

# Prototype Video
## You may refer to this link:
## https://www.linkedin.com/posts/sparsh-mehta-058585158_computervision-fitness-artificialintelligence-activity-6941860351294472192-kyFz?utm_source=share&utm_medium=member_desktop

This repository contains a Python program that uses the Mediapipe library and OpenCV to build a rep counter. The program detects the body landmarks in real-time video feed, calculates the angles between specific joints, and counts the number of repetitions performed.

## Prerequisites

Before running the program, make sure you have the following dependencies installed:

- Python 3
- OpenCV
- Mediapipe

You can install the required packages by running the following command:

### pip install mediapipe opencv-python

## Usage
### To run the program, use Pose Estimator notebook
### The program will open a window displaying the real-time video feed from your webcam. As you perform exercises or movements, the program will detect your body landmarks, calculate the angles, and display the rep count on the screen.

### To exit the program, press the 'q' key.

## Customize
### You can modify the program to suit your specific needs. Here are a few possible modifications:

### Change the joints or angles to be tracked: The program currently calculates the angle between the left shoulder, elbow, and wrist. You can modify the calculate_angle() function to track different joints or calculate different angles.

### Customize the visualization: The program uses OpenCV to draw the detected landmarks and display the rep count on the screen. You can modify the visualization code in the while loop to change the appearance or add additional visual elements.

## Contributing
### Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.



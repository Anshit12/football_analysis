# Football Analysis Project

## Introduction
In this project, we successfully detected and tracked players, referees, and footballs in video footage using YOLO, one of the leading AI object detection models. We trained the model further to enhance its accuracy and performance.
We also implemented a team assignment module that clusters players into teams based on their t-shirt colors, using KMeans for pixel segmentation and clustering. Using this information, we measured each team’s ball acquisition percentage throughout the match.
To account for camera dynamics, we applied optical flow techniques to measure camera movement between frames, which allowed us to more accurately track player movements. Additionally, we performed a perspective transformation to convert pixel coordinates to real-world measurements, enabling us to measure player movement in meters rather than pixels.
Finally, we calculated each player's speed and total distance covered during the match. This project brought together multiple computer vision and machine learning concepts and provided practical solutions to real-world challenges in sports analytics. It has proven valuable for both beginners exploring applied AI and experienced machine learning engineers.
![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1shrWxUYgV-b-JwAC3R_d_s_T_bZvQRbK/view?usp=drivesdk)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1139mx1etH3TOtjvWSC_H3Q0oGHN9f7nY/view?usp=drivesdk)

## Output video
-  [Output video](https://drive.google.com/file/d/13AGPFQw8FPkw1cl7ax-07xxznxGz5oT4/view?usp=drivesdk)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas


  

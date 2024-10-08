
# Project Title

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

![Project Screenshot](/screenshot.png)

## Key Features
- **Object Detection**: Using YOLO to detect and track key elements in the scene.
- **Clustering**: Applying Kmeans for segmentation and categorization based on visual features.
- **Movement Tracking**: Utilizing Optical Flow to capture object movement in terms of speed and distance.
- **Transformation**: Implementing perspective adjustments to calculate actual distances and other metrics.

## Modules Used
This project incorporates the following key modules:
- Use ultralytics and YOLOv8 to detect objects in images and videos.
- Fine tune and train your own YOLO on your own custom dataset.
- Use KMeans to cluster pixles and segment players from the background to get the t-shirt color accurately.
- Use optical flow to measure the camera movement.
- Use CV2's (opencv) perspective transformation to represent the scene's depth and perspective.
- Measure player's speed and distance covered in the image. 

## Pre-Trained Models
- [Trained model link](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view)

## Sample Data
- [Video link](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view)

## Installation Requirements
To run the project, ensure you have the following dependencies installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

## Instructions
1. Clone this repository.
2. Install required packages via `pip install -r requirements.txt`.
3. Run the project with `python main.py` (modify based on actual steps).

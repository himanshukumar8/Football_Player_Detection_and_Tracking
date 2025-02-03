# Football Player Detection and Tracking


## Introduction
YOLO, a top AI object identification model, will be used in this project to identify and follow footballs, players, and officials in films. We'll train the model to improve its performance. To further allocate participants to teams according to the colour of their t-shirts, we will use Kmeans for pixel segmentation and clustering. We can use this information to calculate a team's ball acquisition percentage during a match. To precisely estimate player movement, we'll employ optical flow to track camera movement between frames. In order to track player movement in meters rather than pixels, perspective transformation will be used to record depth and perspective. Lastly, we'll figure out the player's speed and distance travelled.

![display](output_videos/output_video.avi)


## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

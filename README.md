# Optimize traffic flow with YOLO

## Objective
Increasing numbers of cars in cities lead to traffic congestion, delays, and inefficient waiting at empty intersections. To address these challenges, many cities are adopting Intelligent Transportation Systems (ITS) for dynamic traffic management. A key component of ITS involves analyzing live CCTV camera feeds at intersections to monitor traffic conditions. However, manual monitoring is impractical and costly. 

AI-based object detection algorithms can automate this process, interpreting camera images to provide real-time data on vehicle counts and traffic flow, enabling more efficient traffic management and reduced delays.

## Solution
To address traffic congestion and optimize flow at intersections, this project will implement an object detection algorithm to analyze images from traffic cameras and extract valuable information for real-time traffic management.

Using a dataset of approximately 6,000 images collected from live cameras positioned at intersections in X City, I will train a YOLO (You Only Look Once) algorithm to detect five classes of objects:

- Car
- Bus
- Bicycle
- Motorbike
- Person

Once trained, the algorithm will be able to accurately identify these objects at intersections. This information will then be used to assess traffic density and determine the optimal timing for switching traffic lights, ultimately reducing idle wait times and improving traffic flow in real time.

## Achievements
The best model YOLOv8 achieved: 
- mAP50@0.5: 0.93
- F1 score: 0.9

## Conclusion
This project showcased the effectiveness of using YOLO algorithms for real-time traffic monitoring. YOLOv3, YOLOv5, and YOLOv8 were evaluated, with YOLOv8 emerging as the best balance between accuracy and training efficiency. Implementing YOLOv8 can enhance traffic flow management by accurately analyzing camera feeds and optimizing signal timings

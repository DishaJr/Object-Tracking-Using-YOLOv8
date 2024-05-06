# Object Tracking using YOLOv8

This project focuses on implementing object tracking in computer vision using YOLOv8, the latest version in the 'You Only Look Once' series. The goal is to detect and track multiple objects in real-time through video sequences. The project integrates YOLOv8 with advanced tracking algorithms, ByteTrack and BotSort, to enhance tracking accuracy and handle challenging scenarios such as occlusions and varying object sizes.

## Background
Object tracking in computer vision involves the detection and tracking of multiple objects in real-time through video sequences. It is critical in various domains including surveillance, traffic monitoring, and autonomous driving as it enhances the understanding of dynamic scenes and interactions between objects. However, object tracking faces challenges such as dealing with occlusions, varying object sizes, and maintaining identity consistency over time and different perspectives.

## Project Goals and Scope
The main objective of this project is to implement a robust object tracking system using YOLOv8 and advanced tracking algorithms. The project aims to achieve the following goals:

1. Develop a real-time object detection and tracking system.
2. Integrate YOLOv8 with ByteTrack to optimize tracking accuracy and handle occlusions effectively.
3. Incorporate BotSort, an advanced sorting algorithm, to improve tracking accuracy and computational efficiency.

## Features

- Real-time object detection and tracking using YOLOv8.
- Integration with ByteTrack for efficient tracking with minimized identity switches and effective occlusion handling.
- Incorporation of BotSort, an advanced sorting algorithm, to optimize tracking accuracy and reduce computational load.

## Dataset
The project utilizes a custom dataset comprising 2160 images. The dataset includes three distinct categories: Fixed Random Rotate, Linear Movement Rotate, and Rotation Rotate, to evaluate tracking capabilities in various scenarios.

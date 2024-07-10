# Drone-View-Vehicle-Image-Set

## Description

Drone-View-Vehicle-Image-Set consists of 5000 bounding boxes of drone-view vehicles. The annotations for vehicles are provided in two formats: XML and TXT.

This dataset was collected by the research team on Park Street in Madison in 2022. The vehicle trajectories can be found at the following GitHub repository: [Filed-data-Corridor-Vehicle-Trajectory](https://github.com/CATS-Lab/ANL2-Perception-TrajectoryDetection).

## Annotations

The annotations are provided in the following formats:

- XML: Each XML file contains the bounding box coordinates for vehicles in the corresponding image.
- TXT: Each TXT file contains the bounding box coordinates for vehicles in a simple text format.

## Usage
The dataset was previously used for training a YOLOv8 model, achieving remarkable performance. The model attained a precision of 0.9825, recall of 0.9956, and mAP@0.5 of 0.9948. Additionally, the mAP@0.5:0.95 score reached 0.8333. These results indicate that the YOLOv8 model performed exceptionally well, with low false positive and false negative rates, demonstrating robust detection capabilities across various Intersection over Union (IoU) thresholds.

![confusion_matrix](https://github.com/Keke-Long/Drone-View-Vehicle-Image-Set/assets/101722521/15b53f45-6d5e-40bb-a8d9-229ac6b21d7e)

![test_batch0_labels](https://github.com/Keke-Long/Drone-View-Vehicle-Image-Set/assets/101722521/5a9820de-95c3-4d9b-8369-63561045b3e1)

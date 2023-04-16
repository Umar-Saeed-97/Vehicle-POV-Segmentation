
# Vehicle POV Segmentation

The Vehicle POV Segmentation project aims to segment the objects that a car driver sees while driving using YOLOv8 and ByteTrack models. The goal is to create a system that can detect and segment objects such as vehicles, pedestrians in real-time from a camera mounted on the car. The system output is a segmented video stream highlighting objects and potential obstacles for the driver, suitable for applications such as autonomous driving and traffic monitoring. The project is highly customizable and scalable, built with the latest technologies in computer vision and machine learning.

## Snippet

![Example GIF](https://github.com/Umar-Saeed-97/Vehicle-POV-Segmentation/blob/main/Data/video2.gif)

## Requirements

The following packages are required to run the notebook:

- opencv-python
- ultralytics
- supervision


## Usage

Here's how you can use the code in this project:

1. Clone or download the repository to your local machine.

2. Open the Jupyter Notebook file in the repository.

3. Run the cells in the notebook to make detections.

4. You can modify the code to fit your needs.

## Model

This project utilizes the popular YOLOv8 object detection model, which is pretrained on the COCO dataset and achieves high accuracy and speed by dividing the input image into a grid. Additionally, ByteTracker is used for object tracking, a simple and efficient online multi-object tracking algorithm that combines detection and tracking in a unified framework. No custom training was done in this project.

## License

MIT

## Author

[Umar Saeed](https://www.linkedin.com/in/umar-saeed-16863a21b/)
# 🚀 Object Detection using SSDs with PyTorch

This project implements object detection using Single Shot MultiBox Detector (SSD) with pre-trained weights. The SSD can detect various types of objects in video frames with high accuracy, including horses, dogs, people, chairs, and more.

## 📦 Pre-trained Weights

The pre-trained weights for the SSD model are available on Google Drive due to their large size. You can download them from the following link:
[Download Pre-trained Weights](https://drive.google.com/drive/folders/1ZjuU4qKqb7_Z__2YLma6iB3hoanVdY_r?usp=sharing)

## ⚙️ Dependencies

- PyTorch
- TorchVision
- OpenCV
- ImageIO

## 📁 Structure
- ssd.py: Contains the structure of the SSD model.
- data/: Folder containing necessary data and label map.
- epic_horses.mp4: Sample video for object detection.
- object_detection.py: Main Python file for object detection.

## ⚡️ How it Works
The object_detection.py script does the following:

- Loads the pre-trained SSD model.
- Reads each frame from the input video.
- Detects objects in each frame using the SSD model.
- Draws bounding boxes and labels on the detected objects.
- Writes the annotated frames to an output video file.

## 🌐 Scope and Applications
This project can be scaled for real-world applications such as automated traffic systems, surveillance systems, and more.
The efficient object detection provided by SSDs makes it suitable for real-time video analysis.

## 🤝 Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

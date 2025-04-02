# Gun and Knife Detection using YOLO

## Overview
This project demonstrates a YOLO-based object detection model trained to detect guns and knives in images and videos. The model was trained using the [Guns & Knives Object Detection Dataset](https://www.kaggle.com/datasets/iqmansingh/guns-knives-object-detection/data) from Kaggle. The detection system is implemented in a Jupyter Notebook and features a Gradio interface for easy interaction.

## Screenshots
### Image Detection
![Screenshot (367)](https://github.com/user-attachments/assets/22b33a7c-23b4-47c4-aba9-a516cbb3e031)

### Video Detection
https://github.com/user-attachments/assets/32db6b36-67a9-41af-b4df-cfbc1424b0de

## Features
- **Real-time Image and Video Detection**: The model detects guns and knives in both images and videos.
- **YOLO Model**: Trained on a specialized dataset for weapon detection.
- **Gradio Interface**: Provides an easy-to-use web UI for detection.
- **Live Video Processing**: Processes video files frame by frame to detect weapons.

## Dataset
The model was trained using the Kaggle [Guns & Knives Object Detection Dataset](https://www.kaggle.com/datasets/iqmansingh/guns-knives-object-detection/data), which contains labeled images of firearms and knives.


## Usage
### Running the Jupyter Notebook
To run the model and Gradio interface:

1. Open the Jupyter Notebook and run all cells.
2. The Gradio interface will launch, allowing you to upload images and videos for detection.

## Gradio Interface
The project includes a Gradio interface with two tabs:
1. **Image Detection**: Upload an image, and the model will detect guns and knives.
2. **Video Detection**: Upload a video, and the model will process it to detect weapons frame by frame.


## Model Training
The YOLO model was trained using the Ultralytics YOLOv5 framework with custom annotations from the dataset. The trained weights are stored in `runs/detect/train/weights/best.pt`.



# Real-Time Mask Detection System

## Project Timeline

This project was originally developed in 2021 as part of Bachelor's /Mini Project/Batch 3. It has been uploaded to GitHub in 2024 to showcase our work and contributions during that period.

## Project Overview
This Real-Time Mask Detection System employs cutting-edge technologies including Python, TensorFlow, Keras, and OpenCV to detect face masks in real-time feeds, static images, and video streams. Developed as part of a Bachelor's project, this application showcases a practical application of deep learning and computer vision techniques to contribute to public health safety measures amidst global health concerns.

## Key Features
- **Real-Time Detection**: Leverages webcam feeds for instant mask detection, utilizing a pre-trained model to provide live feedback.
- **Image Analysis**: Offers the capability to process and analyze static images for mask detection, marking detected faces with bounding boxes.
- **Video Processing**: Analyzes video files to detect mask usage in each frame, suitable for post-event monitoring.
- **Teachable Machine Integration**: Features integration with Teachable Machine for enhanced real-time detection capabilities, accessible through a user-friendly web interface.

## System Requirements
- Python version 3.6.0 or higher.

## Dependencies
Ensure the following dependencies are installed:
- Keras 2.4.3
- TensorFlow 2.4.0
- OpenCV 3.4.2
- NumPy 1.19.4
- Pillow 8.1.0
- Pandas 1.2.0

Install dependencies using:
```
pip install keras==2.4.3 tensorflow==2.4.0 opencv-python==3.4.2 numpy==1.19.4 Pillow==8.1.0 pandas==1.2.0
```

## Installation
1. Clone the repository to your local machine.
2. Navigate to the cloned directory.
3. Install the required dependencies as listed above.

## How to Use
- **For Real-Time Detection**: Run `MaskDetectorRealTime.py` to start detecting masks in real-time through your webcam.
- **For Static Image Analysis**: Execute `MaskDetectorImages.py`, providing a path to the image file you wish to analyze.
- **For Video File Analysis**: Use `MaskDetectorVideo.py`, specifying the path to the video file for frame-by-frame mask detection analysis.
- **For Teachable Machine-Based Detection**: Open `RealTimeMaskDetectionTeachableMachine.html` in any web browser to use the Teachable Machine model for mask detection.

- Also check the images folder to have a glimpse at our model training, results and accuracy.

## Model Architecture and Training
The mask detection model, built using Keras, features a convolutional neural network (CNN) designed for binary classification tasks. It consists of several convolutional layers, max-pooling layers, and dense layers, trained on a dataset of images categorized into 'mask' and 'no mask'. The model demonstrates effective learning with a high accuracy rate on both training and validation sets.

## Acknowledgments
This project was made possible by the collaborative efforts of our dedicated team, whose contributions have been invaluable. Special thanks to the open-source community for providing the resources and tools that facilitated this project's development.

## Future Work
Future enhancements will focus on improving the model's accuracy and expanding its functionality to include more diverse scenarios and environments, ensuring the system remains robust across different lighting conditions and face orientations.

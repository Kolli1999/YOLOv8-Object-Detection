****YOLOv8 Object Detection****

This repository contains code for real-time object detection using the YOLOv8 model, implemented in Python with OpenCV. The model is pre-trained on the COCO dataset and is capable of detecting various objects in images and video streams.

**Features**

Real-time Object Detection: Uses a pre-trained YOLOv8 model to detect objects in video streams.
Customizable: Easily configure detection confidence and modify class labels.
Random Color Generation: Generates random colors for each detected class for better visualization.
Video Support: Supports video files as input for object detection.

**Requirements**

Python 3.x
OpenCV
Ultralytics YOLO
Numpy

**Installation**

Clone the repository:
git clone https://github.com/Kolli1999/YOLOv8-Object-Detection.git
Navigate to the project directory:
cd YOLOv8-Object-Detection
Install the required dependencies:
pip install -r requirements.txt
**Usage**

Download YOLOv8 Weights:
Make sure you have the YOLOv8 model weights in the weights/ directory.

Prepare Class Labels:
Ensure the class labels file (e.g., coco.txt) is present and contains the labels used by the model.

Run the Object Detection:
Modify the paths in the script to point to your video file or webcam and run the script:
python object_detection.py
Adjust Settings:
Modify confidence thresholds, frame sizes, or other parameters as needed.

**Example Output**

The output will display the video feed with detected objects highlighted and labeled with their respective class names and confidence scores.
**License**

This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgements**
The YOLOv8 model by Ultralytics for the object detection framework.
OpenCV for real-time image processing capabilities.

**Contributing**

Feel free to fork this repository, make improvements, and submit pull requests.

# Vehicle-Detection-and-Tracking-with-Pre-Trained-Object-Detection-Models
 Used YoloV5 and Detectron2 to detect objects 


# Overview
This project aims to detect and track vehicles in a short street scene video using pre-trained object detection models. The workflow involves extracting frames from the video, applying object detection to each frame, and then reconstructing the processed frames into a final video with bounding boxes around detected vehicles. The project is implemented using PyTorch, Detectron2, and YOLOv8 for additional comparison.

# Project Structure
Part 1 - Object Detection Using PyTorch: The main objective is to detect vehicles in a video sequence using a pre-trained model. The steps include:

Frame Extraction: A short street scene video is broken down into individual frames for easier processing.
Inference and Bounding Boxes: A pre-trained object detection model (e.g., Faster R-CNN, YOLO) is used to detect vehicles in each frame, drawing bounding boxes around the detected objects.
Video Reconstruction: The processed frames are combined to create a video with bounding boxes around the vehicles.
Output: Two video files are created – one before inference (original) and one after inference (with bounding boxes).
Part 2 - Object Detection Using Detectron2: For extra credit, the same process is replicated using the Detectron2 framework. This involves:

Setting up the environment for Detectron2.
Applying the Detectron2 model to perform object detection on the video frames.
Visualizing the results with bounding boxes and saving the processed video.
Part 2 Extra - Object Detection Using YOLOv8: As an additional task, the workflow is implemented using YOLOv8:

Setting up YOLOv8 and configuring the model for inference.
Running the model on the street scene video to detect vehicles.
A screenshot of the detection results is provided for demonstration.

# Tools Used
To run the notebooks provided in this project, the following libraries and dependencies are required:

PyTorch: For general deep learning and model inference.
Detectron2: For advanced object detection using Facebook AI's library.
YOLOv8: For quick and efficient object detection.
OpenCV: For handling video processing and frame extraction/reconstruction.
Other standard Python packages: numpy, matplotlib, PIL, etc.

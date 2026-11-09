# Computer Vision Project: AI Object Detection System

## 1. Project Overview

The AI Object Detection System is a computer vision application developed using Python, YOLO, and Streamlit.

The application identifies objects in uploaded images, draws bounding boxes around detected objects, and displays their class names and confidence scores.

## 2. Project Objectives

- Understand the fundamentals of computer vision.
- Implement object detection using a pretrained YOLO model.
- Develop an interactive web application.
- Display object labels and confidence scores.
- Visualize detected objects using bounding boxes.
- Allow users to download the processed image.

## 3. Technologies Used

- Python
- YOLO11n
- Ultralytics
- Streamlit
- OpenCV
- NumPy
- Pillow
- Pandas

## 4. Features

- Upload images in JPG, JPEG, PNG, and WEBP formats.
- Detect multiple objects in an image.
- Display bounding boxes around detected objects.
- Show object names and confidence scores.
- Display the total number of detected objects.
- Display detection coordinates.
- Adjust the minimum confidence threshold.
- Download the annotated image.

## 5. Project Structure

Computer_Vision_Object_Detection/
- app.py
- requirements.txt
- README.md
- venv/

The virtual environment folder is created locally and does not need to be included in the source-code submission.

The pretrained model file may be downloaded automatically when the application runs for the first time.

## 6. Installation Instructions

### Step 1: Install Python

Install a compatible Python version and verify the installation:

    python --version

### Step 2: Create a Virtual Environment

    python -m venv venv

### Step 3: Activate the Environment on Windows

    venv\Scripts\activate.bat

### Step 4: Install Dependencies

    python -m pip install -r requirements.txt

### Step 5: Run the Application

    python -m streamlit run app.py

### Step 6: Open the Application

Open the local URL displayed in the terminal, usually:

    http://localhost:8501

An internet connection may be required to download the pretrained YOLO model on the first run.

## 7. How to Use

1. Start the application.
2. Upload an image.
3. Adjust the minimum confidence threshold if necessary.
4. Click the Detect Objects button.
5. View the annotated image.
6. Review the detection table.
7. Download the resulting image.

## 8. Working Principle

The application uses a pretrained YOLO object detection model.

First, the user uploads an image. The image is passed to the model, which predicts object classes, bounding-box coordinates, and confidence scores.

The application displays the detected objects and draws bounding boxes around them.

The detection results are also presented in a table.

## 9. Applications

- Traffic monitoring
- Retail inventory analysis
- Security and surveillance
- Wildlife observation
- Educational computer vision demonstrations
- Image analysis

## 10. Limitations

- Detection accuracy depends on image quality and model capabilities.
- Small or partially obscured objects may not be detected.
- The model recognizes supported object categories rather than every possible object.
- A compatible computer and sufficient memory are required.
- The first model download requires internet access unless the model is already available locally.

## 11. Conclusion

The project demonstrates how a pretrained deep learning model can be integrated into a Python web application to perform object detection.

It provides practical experience with computer vision, model inference, image processing, and interactive application development.

## 12. Future Improvements

- Add webcam-based real-time object detection.
- Support video uploads.
- Add object counting and category filtering.
- Improve the user interface.
- Train or fine-tune a model for a specialized dataset.

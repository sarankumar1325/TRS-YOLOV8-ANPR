
# TRS YOLOV8 ANPR 

### Project Overview

This project is dedicated to implementing the YOLOv8 (You Only Look Once version 8) object detection model for real-time identification of Indian license plates. The primary focus is on harnessing the capabilities of YOLOv8 to achieve highly accurate and swift license plate detection. Complementing this, the integration of Automatic Number Plate Recognition (ANPR) technology enhances the system's functionality by extracting meaningful information from identified license plates.

## Usage

1. **Image Input:**
   - Users can upload images or use their device's camera for real-time input.

2. **YOLOv8 Detection:**
   - YOLOv8 processes input images, providing precise bounding box coordinates for detected license plates.

3. **ANPR Processing:**
   - ANPR technology extracts alphanumeric characters, transforming raw data into a readable format.

4. **Flask Web Application:**
   - Interact with the system through a user-friendly web interface.
   - Upload images, view detection results, and access ANPR-generated information.

5. **NGROK Hosting:**
   - Ngrok exposes the Flask application and YOLOv8 model online, ensuring remote access.




## Acknowledgements

 - [Ultralytics](https://github.com/ultralytics/ultralytics)
 - [Flask- Ngrok](https://pypi.org/project/flask-ngrok/)
## Authors

- [@Saran Kumar](https://github.com/sarankumar1325)
- [@Ranil Mukesh](https://github.com/ranilmukesh)


## Features

### YOLOv8 Object Detection:
Implement YOLOv8, a state-of-the-art real-time object detection model, to accurately identify and locate license plates within images.

### ANPR Integration:
Utilize ANPR technology to process the detected license plates and extract alphanumeric characters. This step is crucial for converting the license plate information into a usable format.

### Flask Web Application:
Develop a user-friendly web application using Flask, a micro web framework for Python. The application will provide a seamless interface for users to upload images or use their device's camera for real-time license plate detection.

### NGROK Integration:
Use the Ngrok library to expose the Flask application to the internet, allowing for easy sharing and access from external devices. This feature is particularly useful for showcasing the project or making it accessible remotely.












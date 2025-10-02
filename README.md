# Face Recognition System

## Overview
This project is a **Face Recognition System** implemented in MATLAB. It allows the collection of face data, training of a model, and recognition of faces using the trained model. The system can be used for attendance, security, or access control applications.

---

## Features
- Data collection for face images.
- Training of a face recognition model.
- Recognition of faces using the trained model.
- Delete unnecessary or outdated images from the dataset.

---

## File Structure
- `datacollection.m` : Script to capture and save face images for training.
- `modeltraining.m` : Script to train the face recognition model using collected data.
- `model.m` : Script containing the trained model or functions for recognition.
- `deleteimages.m` : Script to delete unwanted images from the dataset.

---

## Requirements
- MATLAB R2018 or later (or compatible version)
- Computer with a webcam for data collection
- Image Processing Toolbox (MATLAB)

---

## Usage
1. **Data Collection**  
   Run `datacollection.m` to capture face images. Ensure good lighting and proper face positioning.  

2. **Training the Model**  
   Run `modeltraining.m` after collecting sufficient images to train the face recognition model.  

3. **Face Recognition**  
   Use `model.m` to recognize faces using the trained model.  

4. **Delete Images**  
   Run `deleteimages.m` to remove unwanted or duplicate images from the dataset.

---

## Contribution
You can contribute by:
- Improving model accuracy
- Adding a GUI interface
- Supporting multiple users simultaneously

---

## License
This project is open-source and free to use. Please give appropriate credit if reused.

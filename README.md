# Currency Detection for the Blind Using Image Processing
## Introduction
Visually impaired individuals face numerous challenges in their daily lives, one of which is identifying currency notes. With a wide range of denominations in circulation, the inability to recognize currency accurately can lead to fraudulent transactions or dependency on others. To tackle this issue, our project implements an image-processing-based currency detection system that assists blind individuals in recognizing Indian currency notes with ease.

This system takes an image input, processes it using deep learning and image processing techniques, and provides an audio output of the detected denomination. This blog will walk you through the project's methodology, algorithms used, results, and future scope.

## Project Objective
The primary goal of this project is to develop an affordable and accessible currency recognition system for the visually impaired. Our approach involves:

Capturing images of currency notes using a camera.
Analyzing the image using machine learning and deep learning techniques.
Extracting features like size, color, watermark, serial numbers, and denomination.
Identifying the currency with high accuracy and providing audio feedback.
Methodology and Implementation
We utilized several machine learning and deep learning models to enhance the recognition accuracy. Here’s an overview of the techniques used:

### 1. Image Preprocessing
Capturing images of different currency denominations.
Converting images to grayscale.
Applying edge detection techniques.
Resizing and normalizing images for uniformity.
### 2. Feature Extraction
Identifying unique characteristics of each currency note.
Using shape, texture, and text detection to differentiate denominations.
### 3. Machine Learning and Deep Learning Models Used
K-Nearest Neighbors (KNN): Used for classifying notes based on extracted features.
Convolutional Neural Networks (CNN): Helps in detecting and classifying different denominations with high accuracy.
Support Vector Machine (SVM): Finds patterns and classifies currency notes into categories.
Region-Based CNN (R-CNN): Enhances accuracy by focusing on the regions of interest in the note.
Transfer Learning: Using pre-trained models to improve recognition accuracy and reduce training time.
### 4. Training and Testing
We collected a dataset of Indian currency notes from INR 10 to INR 2000.
The dataset was trained using deep learning models.
The accuracy was tested across various denominations to ensure reliable recognition.
Results and Performance
Our system was tested with multiple denominations, and here are the results:

Denomination	Time Taken (seconds)	Accuracy (%)
INR 10	             24.6	              84%
INR 20	             40.5	              70%
INR 50	             30.0	              79%
INR 100	             30.0	              79%
INR 200	             36.5	              77%
INR 500	             26.0	              80%
INR 2000	           34.5	              74%

## Key Observations
Notes with clear and high-quality images were detected more accurately.
Orientation and position of the note in the frame played a crucial role.
The system performed best with INR 10 and INR 500 notes.
The model showed room for improvement in detecting INR 2000 notes due to limited dataset availability.
Future Scope and Improvements
Our model currently detects only Indian currency, but it has the potential to be extended to global currency recognition with a larger dataset. Here are some areas for improvement:

### Real-time detection: Implementing a mobile application with real-time recognition.
### Enhanced accuracy: Using more advanced deep learning architectures like YOLO (You Only Look Once) or Vision Transformers.
### Support for damaged or folded notes: Improving recognition capabilities for worn-out or crumpled notes.
### Multi-language support: Adding voice output in multiple languages to assist diverse users.

## Conclusion
This project offers an innovative and accessible solution to assist visually impaired individuals in identifying currency notes accurately. By leveraging deep learning and image processing techniques, we have created a system that can significantly improve financial independence for blind individuals.

If you have any suggestions or ideas for improvement, feel free to contribute or reach out!

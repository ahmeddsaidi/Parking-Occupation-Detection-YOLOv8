# **Automatic Parking Spot Detection Using YOLOv8**

## **Project Overview**

This project aims to contribute to Morocco's digital transformation by developing an **AI-powered system** for automatic parking spot detection and classification. By leveraging **YOLOv8** (You Only Look Once version 8), a cutting-edge deep learning model, the system is capable of detecting free and occupied parking spaces from images in real time. This system can enhance urban mobility, reduce parking congestion, and improve the overall parking experience in cities.

## **Project Objectives**
- Develop a parking spot detection system using YOLOv8 for real-time applications.
- Align the project with Morocco's digital transformation goals by improving urban mobility with AI technology.
- Provide the foundation for integration into real-time camera systems and mobile apps for accessible parking management.

## **Technologies Used**
- **YOLOv8** (for object detection)
- **Python** (for training the model and developing scripts)
- **OpenCV** (for image processing)
- **TensorFlow** or **PyTorch** (depending on your implementation choice)
- **Mobile App** (for showcasing the integration of the detection system with a real-time user interface)

## **Dataset**
- **PKLot Dataset**: A comprehensive dataset containing annotated images of parking spaces, both free and occupied, used for training and evaluation.

## **How It Works**
1. **Data Collection**: We use the PKLot dataset, which provides real-world images of parking lots and includes annotations to specify whether each parking spot is free or occupied.
2. **Training YOLOv8**: The YOLOv8 model is trained to recognize parking spaces, differentiating between occupied and free spots using the dataset images.
3. **Integration with Mobile App**: The system is integrated with a mobile app that allows users to access real-time parking spot information, making the process of finding available parking more efficient.

## **Key Features**
- **Real-Time Detection**: The model is optimized to detect parking spots instantly, making it suitable for dynamic urban environments.
- **High Precision**: With a focus on accuracy, the system classifies parking spots with near-perfect precision, providing reliable results for users.
- **Mobile Integration**: The project showcases the potential to integrate the detection system into a mobile app, offering an easy-to-use interface for users.

## **Screenshots**

### **Prediction Results**
Below are examples of the predictions made by the YOLOv8 model on parking lot images:

![Prediction Example 1](path_to_your_prediction_image_1)
*Example 1: Detected free and occupied parking spots.*

![Prediction Example 2](path_to_your_prediction_image_2)
*Example 2: Real-time parking spot detection in action.*

### **Mobile App Interface**
Here’s a preview of the mobile app that integrates with the parking detection system:

![Mobile App Screenshot](path_to_your_mobile_app_image)
*Mobile app interface showing real-time parking spot availability.*

## **Installation & Setup**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/parking-spot-detection.git
   cd parking-spot-detection

2. **Install dependencies: You’ll need Python 3.x and the following libraries**:
   ```bash
   pip install -r requirements.txt

3. **Run the model: To test the model on your own images, you can use the following command**:
   ```bash
   python detect_parking.py --input_image your_image.jpg

   

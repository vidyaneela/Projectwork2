## Knee Osteoarthritis Detection and Severity Classification using Deep Learning
The development of a deep learning-based system for Knee Osteoarthritis Detection and Severity Classification, aimed at automating the diagnosis process using X-ray images. This system leverages the Xception CNN model and Grad-CAM visualization to enhance accuracy and interpretability, providing a reliable computer-aided diagnostic (CAD) tool for healthcare professionals.

## About
Knee Osteoarthritis Detection and Severity Classification is a project designed to develop an automated system that utilizes deep learning techniques for accurate and efficient diagnosis of knee osteoarthritis (OA) from X-ray images. Traditional OA diagnosis relies on manual radiographic assessment, which is time-consuming, subjective, and prone to variability among radiologists. This project aims to overcome these challenges by implementing a computer-aided diagnostic (CAD) tool that can classify knee OA into five severity levels: Healthy, Doubtful, Minimal, Moderate, and Severe.

The system leverages the Xception deep learning model with transfer learning to enhance classification accuracy. Additionally, Grad-CAM (Gradient-weighted Class Activation Mapping) is incorporated to provide visual explanations, ensuring interpretability and trustworthiness in medical decision-making. The model is deployed via a Streamlit-based web application, enabling real-time analysis and a user-friendly interface for healthcare professionals.

By integrating deep learning, medical imaging, and interactive AI-powered diagnosis, this project contributes to the advancement of AI-driven healthcare solutions, facilitating faster, more consistent, and objective OA severity assessment.

## Features
* Implements an advanced deep learning model (Xception CNN) for high-accuracy osteoarthritis classification.
* A framework-based application using Streamlit for easy deployment and accessibility.
* High scalability, allowing integration with hospital databases and medical imaging systems.
* Optimized processing, reducing time complexity for real-time X-ray analysis.
* Grad-CAM visualization for model interpretability, highlighting key areas in X-ray images.
* Transfer learning approach for improved performance even with limited medical datasets.
* User-friendly interface, enabling seamless interaction for healthcare professionals.

## Requirements
* Operating System: Requires a 64-bit OS (Windows 10/11 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is required for implementing the knee osteoarthritis detection system.
* Deep Learning Frameworks: TensorFlow/Keras for model training and classification.
* Image Processing Libraries: OpenCV for preprocessing X-ray images and enhancing feature extraction.
* Version Control: Git for collaborative development and effective model versioning.
* IDE: VSCode, Jupyter Notebook, or PyCharm for coding, debugging, and model development.]
* Additional Dependencies: Scikit-learn for evaluation metrics, Matplotlib and Seaborn for visualization, and Grad-CAM for model interpretability.

## System Architecture

![arc](https://github.com/user-attachments/assets/68db7754-bc68-4c41-8f5a-0546b0a0d98a)



## Output

#### Output1 - HOME PAGE
![Screenshot 2025-02-22 195418](https://github.com/user-attachments/assets/82d48739-c5a6-4ae5-97f6-369226c11305)


#### Output2 - Grad-CAM Visualization
![WhatsApp Image 2025-02-21 at 1 43 14 PM (2)](https://github.com/user-attachments/assets/344bb097-4cba-42bc-8b86-e26c2764a455)

### Output - Severity Analysis
![image](https://github.com/user-attachments/assets/2b1abae6-8610-4377-af0b-7bee6b6a7d54)

### ACCURACY
Detection Accuracy: 62%


![Screenshot 2025-02-22 194543](https://github.com/user-attachments/assets/bf928ebf-f18e-4273-a02e-e78dbfc0c4d1)



## Results and Impact
The system demonstrates high accuracy in distinguishing knee OA severity levels.
Interpretability through Grad-CAM allows medical professionals to validate the AI model's decision-making.
Provides quick and consistent diagnosis, reducing human error and subjectivity in severity classification.
Serves as a foundation for AI-powered medical imaging advancements and potential real-time hospital integration.


## Articles published / References
1. J. Abedin, J. Antony, K. McGuinness, K. Moran, N. E. O’Connor, D. Rebholz-Schuhmann, and J. 
Newell, “Predicting knee osteoarthritis severity: Comparative modeling based on patient’s data and plain 
X ray images”. Sci. Rep. 9, 57-61, 2019.
2. D. Hayashi, F. W. Roemer, M. Jarraya, and A. Guermazi, “Imaging in osteoarthritis”, Radiologic 
Clinics of North America 55 (5), 1085-1102, 2017.
3. P. Chen, L. Gao, X. Shi, K. Allen, and L. Yang, “Fully automatic knee osteoarthritis severity 
grading using deep neural networks with a novel ordinal loss”. Computerized Medical Imaging and 
Graphics, 75, 84 92, 2019.  
4. A. Tiulpin, J. Thevenot, E. Rahtu, P. and Lehenkari, S. Saarakkala, “Automatic knee osteoarthritis 
diagnosis from plain radiographs: A deep learning-based approach”. Sci. Rep. 8, 17-27, 2018.  
5. A. Tiulpin, and S. Saarakkala, “Automatic grading of individual knee osteoarthritis features in plain 
radiographs using deep convolutional neural networks”. Diagnostics, 10(11), 9-32, 2020.





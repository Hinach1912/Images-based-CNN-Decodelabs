# Brain Tumor Classification using Deep Learning

## Project Overview
- Developed a deep learning-based system for **Brain Tumor Classification** using MRI images.  
- The model classifies brain tumors into two categories:  
  - **High-Grade Tumor**  
  - **Low-Grade Tumor**  

## Dataset
- Total dataset contains **6,674 MRI images**.  
- **High-Grade Tumor:** 3,453 images  
- **Low-Grade Tumor:** 3,221 images  
- Dataset is balanced for binary classification tasks.  

## Models Used
- **CNN (Convolutional Neural Network)**  
  - Used as a baseline model for image classification.  
  - Extracts spatial features from MRI images.  

- **Inception-V3**  
  - Used transfer learning for improved feature extraction.  
  - Handles multi-scale image patterns effectively.  

- **ResNet-50**  
  - Deep residual network with skip connections.  
  - Improves classification accuracy in deep architectures.  

- **MobileNet**  
  - Lightweight and efficient model for faster prediction.  
  - Suitable for real-time medical image analysis.  

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  
- OpenCV  

## Project Workflow
1. Data preprocessing and image resizing  
2. Data augmentation for improved generalization  
3. Model training using multiple architectures  
4. Performance evaluation and comparison  
5. Brain tumor prediction and classification  

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

## Results
- Compared performance of CNN, Inception-V3, ResNet-50, and MobileNet.  
- Identified the best-performing model for brain tumor classification.  

## Future Work
- Multi-class tumor classification  
- Real-time deployment for hospital diagnosis systems  
- Integration with web application  

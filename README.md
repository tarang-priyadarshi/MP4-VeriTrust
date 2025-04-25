# MP4-VeriTrust
# Indian Currency Note Classification and Damage Detection

## Overview
-----------

This project aims to develop a comprehensive system for classifying Indian currency notes by their denomination and detecting whether they are damaged or undamaged. T

### Models
* **Denomination Classification Model**: Classifies Indian currency notes into their respective denominations (e.g., ₹10, ₹20, ₹50, etc.).
* **Damage Detection Model **: Takes an image of a banknote as input and outputs a binary classification, indicating whether the banknote is damaged or undamaged.

## Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, PyTorch, OpenCV, NumPy, Matplotlib  
- **Models:** 
  - Custom Convolutional Neural Network (CNN)  
  - PyTorch-based CNN for improved accuracy
- **Optimizers:** Adam (Custom CNN), Adam (PyTorch)  
- **Loss Functions:** Binary Crossentropy (Custom CNN), Cross-Entropy Loss (PyTorch)


## Model Training & Results
- **Custom CNN Model (84% Accuracy)**
  - Trained using TensorFlow/Keras on an augmented dataset of Indian currency images
  - Validation accuracy of 84% for condition classification
- **PyTorch CNN Model (90% Accuracy)**
  - PyTorch model trained with similar data and preprocessing steps
  - Achieved 90% accuracy on multi-class currency denomination classification and improved condition detection



## PPT
[🔗 VeriTrust Project PPT]
(https://www.canva.com/design/DAGCpWqLNOc/LMhYLHl4p-JOLDy9vViRAQ/view?utm_content=DAGCpWqLNOc&utm_campaign=designshare&utm_medium=link&utm_source=editor)

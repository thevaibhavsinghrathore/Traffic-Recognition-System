# Traffic Sign Recognition System

This project implements a deep learning-based Traffic Sign Recognition System using Convolutional Neural Networks (CNNs). It classifies road signs such as speed limits, turns, and pedestrian warnings, which are critical components in autonomous driving and driver-assist technologies.

## Objective

To develop a robust model that accurately recognizes and classifies traffic signs from images captured under varying real-world conditions, aiding in the development of safe self-driving systems.

## Model Overview

- Developed using TensorFlow and Keras with a CNN architecture
- Trained on a labeled dataset of traffic sign images
- Achieves over 92% accuracy on test data
- Handles noisy, low-resolution, and distant images

## Dataset Structure

/Traffic_sign_Recognition/  
├── Train/  
│   ├── 0/  
│   ├── 1/  
│   └── ...  
└── Test/  
    ├── Images/  
    └── labels.csv  

## Features

- Preprocessing with normalization and resizing
- Data augmentation to improve generalization
- Classification of over 40 traffic sign categories
- Modular code structure for easy extension
- Ready for real-time integration

## Results

- Test accuracy: ~92%
- Tools used: Python, TensorFlow, OpenCV, NumPy, Pandas, Scikit-learn

## Future Work

- Real-time detection from live video feeds
- Integration with object detection for sign localization
- Deployment using Flask API or mobile applications

## License

This project is licensed under the MIT License.

## Author

[Your Name]

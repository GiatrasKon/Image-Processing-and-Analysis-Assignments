
# Image Processing and Analysis Assignments

This repository contains two assignments from the "Image Processing and Analysis" graduate course of the MSc Data Science & Information Technologies Master's programme (Bioinformatics - Biomedical Data Science Specialization) of the Department of Informatics and Telecommunications department of the National and Kapodistrian University of Athens (NKUA), under the supervision of professor Vasileios Katsouros, in the academic year 2023-2024. Each assignment explores various image processing techniques, ranging from enhancement and transformation to intelligent systems for medical imaging. The repository includes Python notebooks and related documentation, providing detailed explanations, workflows, and results.

## Assignment 1: Image Processing Techniques

A set of exercises focusing on fundamental image processing methods, including image enhancement, transformation, and edge detection.

**Key Tasks:**
- Applied grayscale transformations to analyze their effects on intensity values and brightness.
- Enhanced images to improve light, color, and perceived brightness.
- Sharpened images using spatial filters.
- Analyzed edges and geometric properties of objects in images.

**Main Results:**
- Visualized improvements in brightness, color, and sharpness.
- Detected and analyzed structural features, such as edges and corners.
- Successfully approximated enhancement pipelines for specific image tasks.

## Assignment 2: Pneumonia Detection in Chest X-Rays

Developed an intelligent system to detect pneumonia in chest X-ray images using classical and deep learning methods.

**Key Tasks:**
- Explored and preprocessed the Kaggle dataset: [Chest X-ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).
- Implemented detection algorithms using:
    - Classical machine learning techniques (e.g., feature-based methods).
    - Neural network architectures for automated feature extraction and classification.

**Main Results:**
- Achieved high detection accuracy, with performance metrics including confusion matrices and classification reports.
- Compared the effectiveness of classical and neural network approaches.

## Cloning the Repository

```sh
git clone https://github.com/GiatrasKon/Image-Processing-and-Analysis-Assignments.git
```

## Package Dependencies

This project uses several Python libraries for image processing, machine learning, and deep learning tasks. Ensure you have Python 3.7 or higher installed on your system. Below is the list of required packages:

Assignment 1:
- numpy
- Pillow
- scikit-image
- opencv-python
- matplotlib

Assignment 2:
- numpy
- pandas
- matplotlib
- seaborn
- Pillow
- opencv-python
- pathlib
- scikit-learn
- optuna
- scikit-image
- torch
- torchvision
- torchsummary

You can install all the dependencies at once using the following command:

```sh
pip install numpy Pillow scikit-image opencv-python matplotlib pandas seaborn pathlib scikit-learn optuna scikit-image torch torchvision torchsummary
```

---
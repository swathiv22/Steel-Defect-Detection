# Steel Defect Detection with YOLOv11

This project aims to develop an **object detection model** using **YOLOv11** to automatically identify and classify surface defects in steel materials. The defects include cracks, pits, and inclusions, which are often hard to detect manually but are critical for quality control in the steel manufacturing industry.

## Overview

The model is trained using a custom dataset provided by **Roboflow**, which includes images of steel surfaces with annotated defects. By leveraging the **Ultralytics YOLOv11** framework, we can train the model for efficient defect detection with high accuracy.

The project aims to automate quality inspection in industries, reducing the need for manual inspection, improving efficiency, and ensuring high product quality.

## Features

* **Defect Detection**: Detects and classifies defects like cracks, pits, and inclusions on steel surfaces.
* **Custom Dataset**: Utilizes a custom dataset obtained from **Roboflow** with labeled defects.
* **Model Training**: Uses **YOLOv11** for training the object detection model, providing high-speed inference and real-time detection capabilities.
* **Validation & Inference**: Includes validation of the model's performance on unseen images and inference to predict defects in new images.

## Tools and Technologies

* **Python**: Programming language used for training and model deployment.
* **Ultralytics YOLOv11**: A state-of-the-art object detection model used to detect defects.
* **Roboflow**: A platform used to manage and preprocess the dataset for training.
* **Google Colab**: Used as the platform for model training with GPU support.

## Installation

To run this project locally, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/steel-defect-detection.git
cd steel-defect-detection
pip install -r requirements.txt
```



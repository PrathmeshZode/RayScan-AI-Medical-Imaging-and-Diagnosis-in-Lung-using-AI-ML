# RayScan-AI-Medical-Imaging-and-Diagnosis-in-Lung-using-AI-ML

RayScan AI is an advanced AI-based diagnostic system designed to detect lung diseases such as pneumonia, COVID-19, and lung cancer from chest X-ray images. This system integrates several powerful technologies, including deep learning, computer vision, and medical imaging techniques, to enhance diagnostic accuracy and assist healthcare professionals in making quicker decisions.

## Technologies Used

- **VGGNet-16** and **InceptionNet**: Pre-trained convolutional neural networks used for feature extraction and disease classification.
- **OpenCV** and **CLAHE**: Used for image preprocessing, enhancing image contrast and quality to improve model performance.
- **Grad-CAM**: Helps generate heatmaps to highlight critical regions of the X-ray image that influence the model’s predictions, enhancing model interpretability.

## How It Works

1. **Feature Extraction & Classification**: The system uses VGGNet-16 and InceptionNet to classify X-ray images into specific lung disease categories. These models are trained on large chest X-ray datasets to identify disease-specific patterns.
2. **Image Preprocessing**: X-ray images are preprocessed using OpenCV and CLAHE to improve their contrast and quality, ensuring better results from the model.
3. **Interpretability**: Grad-CAM is used to generate heatmaps, providing transparency by showing which regions of the image most influenced the model's prediction.

## Technology Stack

- **Python**: The programming language used to develop the system.
- **TensorFlow**: Used for implementing deep learning models and training the system.

## Features

- Real-time image input and prediction output.
- User-friendly interface.
- Cost-effective and fast diagnostic tool, especially useful in areas with limited access to radiologists.

## Potential Use Cases

RayScan AI is designed to be beneficial in healthcare settings, particularly in regions with limited access to radiologists, by offering a reliable, fast, and cost-effective diagnostic aid.

---

Feel free to explore, contribute, or use this project as a starting point for further research in medical AI-based diagnostics.

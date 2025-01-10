# Potato Leaf Disease Detection using CNN and Quantization

This project focuses on detecting diseases in potato leaves using Convolutional Neural Networks (CNN) and image quantization techniques. It aims to classify potato leaves into three categories: **Healthy**, **Early Blight**, and **Late Blight**, by leveraging a preprocessed and quantized dataset.

## Dataset
The dataset contains labeled images of potato leaves in three classes:
- **Healthy**
- **Early Blight**
- **Late Blight**

### Preprocessing Steps
1. **Cropping**: Cropped each image to focus on the leaf area, removing unnecessary background noise.
2. **Quantization**: Applied quantization to divide the pixel intensity values into 5 discrete parts, reducing noise and emphasizing key features.
3. **Data Splitting**: Split the dataset into training and testing parts for model evaluation.

## Model Architecture
The model is a Convolutional Neural Network (CNN) designed to extract and learn spatial features from the preprocessed images. The architecture consists of:
- **Convolutional Layers**: Extract feature maps.
- **Pooling Layers**: Reduce spatial dimensions while retaining essential features.
- **Fully Connected Layers**: Perform classification into the three leaf conditions.
- **Activation Functions**: ReLU for non-linearity and Softmax for output probabilities.

## Implementation
1. **Libraries Used**:
   - Python (3.8+)
   - TensorFlow/Keras
   - NumPy
   - Matplotlib
   - OpenCV (for preprocessing)

2. **Training**:
   - Optimizer: Adam
   - Loss Function: Categorical Crossentropy
   - Evaluation Metrics: Accuracy and Loss

3. **Visualization**:
   - Displayed sample preprocessed images.
   - Generated accuracy vs. loss graphs.
   - Created confusion matrices for performance analysis.

## Key Features
- **Image Visualization**: Displayed cropped and quantized images for verification.
- **Graphical Analysis**: Plotted training and testing metrics (accuracy, loss).
- **Confusion Matrix**: Highlighted class-wise performance.

## Results
- Model performance metrics:
  - Training Accuracy: [Insert Value]
  - Testing Accuracy: [Insert Value]
  - Confusion Matrix: [Insert Graph/Image]

## Future Work
- Enhance model robustness by adding augmentation techniques.
- Experiment with different quantization levels and preprocessing methods.
- Extend the dataset to include more leaf images for better generalization.


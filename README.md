# Plant Disease Detection using Deep Learning

**Project Overview**

This project aims to develop an AI-powered system to detect plant diseases early in fruit crops like peaches, strawberries, grapes, and cherries. By leveraging deep learning techniques, specifically Convolutional Neural Networks (CNNs) and transfer learning with MobileNetV2, the system can accurately identify disease symptoms from leaf images.

**Motivation**

* **Food Security:** Timely disease detection helps prevent crop loss and ensure a stable food supply.
* **Farmer Support:** Early intervention reduces financial losses for farmers.
* **Public Health:** Consuming disease-infected fruits can pose health risks.

**Dataset**

The dataset used for training and testing the models includes a variety of leaf images affected by different diseases. The images are pre-processed to enhance image quality and extract relevant features.

**Methodology**

1. **Data Preprocessing:**
   - Image resizing and normalization
   - Data augmentation (rotation, flipping, zooming)
   - Splitting into training, validation, and testing sets

2. **Model Development:**
   - **CNN Model:**
     - Multiple convolutional layers for feature extraction
     - Max pooling layers for dimensionality reduction
     - Dense layers for classification
   - **MobileNetV2 Model:**
     - Transfer learning approach using pre-trained MobileNetV2
     - Fine-tuning the top layers for disease classification

3. **Model Training:**
   - Using categorical cross-entropy loss and Adam optimizer
   - Hyperparameter tuning to optimize performance

4. **Model Evaluation:**
   - Assessing accuracy, precision, recall, and F1-score on the test set

5. **User Interface:**
   - Developing a user-friendly GUI for easy interaction
   - Allowing users to upload leaf images
   - Providing real-time disease prediction and recommendations

**Results**

- **CNN Model:**
   - Training accuracy: 95.85%
   - Validation accuracy: 92.29%
   - Testing accuracy: 83.33%
- **MobileNetV2 Model:**
   - Training accuracy: 97.15%
   - Validation accuracy: 98.75%
   - Testing accuracy: 88.89%

**Future Work**

- Expand the dataset to include more diverse plant species and disease types.
- Explore advanced deep learning techniques like attention mechanisms and transformers.
- Develop a mobile application for on-field disease detection.
- Integrate with IoT devices for real-time monitoring and alerts.

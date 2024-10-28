**Detection of COVID-19 from CT Images Using Deep Convolutional Neural Network**

**Project Overview**

This project aims to enhance COVID-19 diagnosis using CT images by employing a Convolutional Neural Network (CNN) model, specifically the DenseNet-161 architecture, to classify CT scans into three categories: Normal, Pneumonia, and COVID-19. This tool can support healthcare professionals by providing rapid and accurate screening to complement RT-PCR testing.

**Dataset**

The model is trained on the COVIDx-CT dataset, which consists of:

104,009 Chest CT slices from 1,489 patient cases.

Categories include Normal, Pneumonia (non-COVID), and COVID-19 pneumonia cases.

**Data Preparation**

Normalization: Images are normalized, grayscaled, and resized for uniform input.

Augmentation: Techniques such as random rotation, flipping, and resampling are applied to balance the dataset and enhance generalization.

**Model Architecture**

The model uses DenseNet-161, a CNN architecture known for its dense connections and ability to handle complex feature extraction.

DenseNet’s advantages include reduced vanishing gradient issues, strengthened feature propagation, enhanced feature reuse, and a lower parameter count.

**Implementation**

Hyperparameters:

Growth Rate: 32

Epochs: 3

Optimizer: Adam

Loss Function: Cross Entropy Loss

Performance Metrics: Precision, Recall, F1-Score, and Confusion Matrix are computed for each category.

**Comparison with Other Models**

DenseNet-161 was compared with other CNN architectures, including Vgg16, Vgg19, ResNet101, ResNet152, and DenseNet201. DenseNet-161 yielded the highest accuracy, demonstrating superior classification performance for COVID-19 detection.

**Results**

Accuracy: 95.3%

Metrics: Precision, Recall, and F1-score were high across all categories, indicating robust model performance.

**Future Scope**

Further development includes:

Increasing dataset size for improved accuracy.

Exploring gender-based classification to analyze potential demographic trends.

Enhancing feature engineering for better prediction accuracy.

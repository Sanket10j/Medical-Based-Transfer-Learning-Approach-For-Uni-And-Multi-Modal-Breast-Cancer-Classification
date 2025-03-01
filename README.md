# Medical-Based-Transfer-Learning-Approach-For-Uni-Multi-Modal-Breast-Cancer-Classification

According to WHO, more than 2.3 million new cases of breast cancer occur each year worldwide, which makes it the most common type of cancer among women. Breast cancer treatment can be highly effective at an early stage. However individual medical diagnostic methods have limitations in covering the whole spectrum of complexity to detect cancer in the early phase, which motivates to consider multiple medical image modalities to make a more accurate diagnosis. 

The first aim of the project was to apply medical-based pre-trained CNN models on individual medical image modalities. The next objective is to create a feature-level fusion-based multimodal CNN classification models using the most accurate pre-trained model found for each image modality. In the project, four pre-trained models (DenseNet121, Resnet50, Inception-v3, Inception-Resnet-v2 CNN architectures) with RadImagenet weights have been used on three specific breast image modalities datasets: Mammograms, Ultrasound, and Thermal images, where each dataset was divided into malignant, benign, and normal classes. 

Almost all models performed well after fine-tuning, with Inception-ResNet-v2 achieving the highest accuracy across all modalities: 66% for Mammograms, 81% for Ultrasound, and 99% for Thermal datasets. Furthermore, Method 1 outperformed Method 2 in terms of accuracy, as it utilized a single model instead of three distinct models to construct the multimodal CNN. Method 1 gave 78%, 87%, and 99% accuracy for Mammograms, Ultrasound, and Thermal datasets respectively surpassing the accuracy of any unimodal approach.



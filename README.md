# Medical-Based-Transfer-Learning-Approach-For-Uni-Multi-Modal-Breast-Cancer-Classification

According to WHO, more than 2.3 million new cases of breast cancer occurs each year
worldwide, which makes it the most common type of cancer among women. Breast cancer
treatment can be highly effective at an early stage. But individual medical diagnostic methods
have limitations to cover up whole spectrum of complexity to detect cancer in early phase,
which motivates to consider multiple medical image modalities to make diagnosis.

The first aim of the project was to apply medical based pre-trained CNN models on different medical
image modalities separately, changing the parameters of settings for these models, and using
data augmentations methods to the medical images to get better classification accuracy. In the
next step, to create feature-level fusion based multimodal CNN classification model using
most accurate pre-trained model found for each image modality. During this work, have used
five different models on three specific breast image modalities datasets: Mammograms,
Ultrasound and Thermal images, where each dataset divided into malignant, benign and
normal classes and also implemented RadImagenet and chexnet weights on DenseNet121,
Resnet50, Inception-v3, Inception-Resnet-v2 CNN architectures.

Almost all models performed well after fine-tuning except chexnet, but Inception-Resnet-v2 showed the best
result across all modalities with 66%, 81%, 99% accuracy for Mammograms, Ultrasound and
Thermal dataset respectively. In addition, it performed better at accuracy as single model
used in method1 than three distinct models to create multimodal CNN model mentioned in
method 2.



## Lung and Colon Cancer Detection Using Convolutional Neural Networks with InceptionV3 and Data Augmentation
### Project Overview
This project aimed to classify lung and colon cancer presence using medical imaging data with the help of Convolutional Neural Networks (CNNs). The model leveraged InceptionV3, a pre-trained CNN, combined with data augmentation and image preprocessing to improve accuracy and robustness.
### Objectives
Preprocess and augment medical imaging data.
Utilize InceptionV3 for transfer learning on the dataset.
Achieve optimal classification accuracy through CNN training.
### Data Preparation
1. Rescaling & Normalization:
Pixel values were scaled between 0 and 1 to standardize input images.
2. Data Augmentation:
Techniques like rotation, zooming, flipping, and shifting expanded the dataset to mimic real-world variability and improve generalization.
3. Image Generation:
Augmented images were prepared for training, validation, and testing.
### Model Architecture
InceptionV3 was used as the pre-trained base model, with its final layers fine-tuned for the binary classification task (cancer present vs. absent).
### Results
The model achieved a test accuracy of 80%, demonstrating its ability to classify unseen medical images effectively.
### Conclusion
The project successfully applied CNNs with InceptionV3 and data preprocessing techniques to classify lung and colon cancer imaging data with 80% test accuracy. This highlights the potential of CNNs and transfer learning in medical diagnostics.




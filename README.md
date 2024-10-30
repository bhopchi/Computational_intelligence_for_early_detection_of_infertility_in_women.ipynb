# Computational_intelligence_for_early_detection_of_infertility_in_women.ipynb
Project on infertility detection in women using CNN models on 3,832 fetal head ultrasound images. Data were preprocessed, augmented, and analyzed with models (Simple CNN, Xception, and Inception with Attention). The Simple CNN model excelled in accuracy (F1=0.93). Open-source data supports further medical imaging research.

Project Overview: Detection of Female Infertility Using Inception and Xception with Attention Mechanism

Access Code: Find the project code, where a link to that particular code is available on this comment section.

I utilized a dataset of fetal head ultrasound images in this study, comprising 3,832 anonymized images, licensed under Creative Commons Attribution 4.0 (CC BY 4.0) at a resolution of 959 x 661 pixels. The dataset comprises four categories: Trans-thalamic, Trans-ventricular, Trans-cerebellum, and diverse fetal head images. It is, therefore, a great asset for medical imaging research, as it respects patient anonymity.

Data Preprocessing

The data preparation step included loading images, resizing to a uniform size, normalizing pixel values between 0 and 1, and using several data augmentation processes like rotation and flipping of images to increase model strength and minimize overfitting.

Model Implementation

Below are the CNN models implemented for image classification:

1. Simple CNN: A simple base model for baseline classification.


3. Xception: Employing depthwise separable convolutions to improve the computational effectiveness.

4. Xception with Attention: It applies the attention mechanism for focusing the most important features.

5. Inception with Attention: It introduces the mechanism of attention to improve feature representation.

Each model was evaluated in terms of precision, recall, and F1 score on a validation set.

Results Analysis
The result metrics for each model are given below:
Simple CNN: Precision 0.94, Recall 0.93, F1 Score 0.93.

Inception: Precision 0.86, Recall 0.79, F1 Score 0.79.

Xception: Precision 0.85, Recall 0.82, F1 Score 0.81.

Xception with Attention: Precision 0.84, Recall 0.74, F1 Score 0.74.

Inception with Attention: Precision 0.45, Recall 0.36, F1 Score 0.22 (lowest performance).

 

The Simple CNN performed better, hence validating the use of the network for fetal head ultrasound images classification, and the Inception with Attention model did not perform well in this experiment.

Conclusion

This project embodies the heterogeneous nature of effectiveness of various CNN architectures for classifying fetal head ultrasound images. Being open-access, the database tends to encourage multi-institutional research as well as future development of medical imaging.

#MedicalImaging #Ultrasound #DeepLearning #ComputerVision #CNN #AttentionMechanism #Xception #Inception #FetalHealth #AIinHealthcare #DataScience #MachineLearning #Infertility #MedicalResearch #OpenScience

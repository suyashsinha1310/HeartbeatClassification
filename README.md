# HeartbeatClassification
# Heartbeat-Classification-Aiml-project
Description:
This project focuses on building a robust Convolutional Neural Network (CNN) model for ECG heartbeat classification using the MIT-BIH Arrhythmia Dataset. Gaussian noise is added to the training and testing datasets to simulate real-world noisy ECG signals. 

The workflow includes:

-> Gaussian Noise Injection: Introducing controlled Gaussian noise to ECG signals for assessing model robustness.
-> Model Evaluation: Evaluating the pre-trained model's performance on noisy data.
-> Transfer Learning: Leveraging a pre-trained ECG model, freezing its layers, and adding new dense layers to fine-tune for noisy signals.
-> Fine-Tuning: Unfreezing pre-trained layers and training with a lower learning rate for better adaptation to noisy data.
-> Performance Metrics: Generating confusion matrices to compare performance across noisy and clean datasets.

This approach enhances the model's ability to classify five heartbeat categories:

-Normal beats
-Unknown beats
-Ventricular ectopic beats
-Supraventricular ectopic beats
-Fusion beats

Key features include noise simulation, transfer learning, fine-tuning, and robust evaluation to ensure the model performs well in real-world noisy environments.
#

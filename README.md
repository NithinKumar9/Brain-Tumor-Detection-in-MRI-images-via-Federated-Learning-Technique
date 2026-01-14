# Brain-Tumor-Detection-in-MRI-images-via-Federated-Learning-Technique
This repository presents a privacy-preserving brain tumor detection system built using Federated Learning (FL) and deep learning architectures applied to MRI images. The primary objective of this project is to enable accurate brain tumor classification while ensuring patient data confidentiality by avoiding centralized data storage.

The system leverages VGG16 and DenseNet convolutional neural networks trained in a federated environment using the Federated Averaging (FedAvg) algorithm. Multiple clients (simulating healthcare institutions) perform local training on their MRI datasets, and only model parameters are shared with a central server for aggregation. This approach ensures compliance with data privacy regulations such as HIPAA and GDPR.

The pipeline includes image preprocessing, feature extraction, local model training, federated aggregation, and global model evaluation. The model classifies MRI scans into four categories: Glioma, Meningioma, Pituitary Tumor, and No Tumor. Performance is evaluated using accuracy, precision, recall, and F1-score, demonstrating strong and consistent results across federated clients.

This project highlights the feasibility of deploying collaborative AI solutions in healthcare without compromising sensitive data. It serves as a practical implementation for researchers and developers interested in medical imaging, federated learning, and secure AI systems.

# Dataset
Dataset from kaggle

# Report
For Project Report DM to nithinbyadav999@gmail.com

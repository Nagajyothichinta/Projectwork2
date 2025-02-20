## Title of the Project
## OSIC Pulmonary Fibrosis Progression
## About

Pulmonary fibrosis exists as a continuous deteriorating lung disorder that causes lung tissue scarring (fibrosis) which gradually reduces respiratory capacity throughout time.
The scarring process in the lungs increases tissue density and stiffness which blocks oxygen transfer to blood cells thus causing symptoms of breathlessness along with chronic coughing and persistent fatigue.
The main variation of this condition is Idiopathic Pulmonary Fibrosis (IPF) since experts have yet to identify its root cause. Additional types of pulmonary fibrosis emerge from environmental substances, autoimmune illnesses, infectious agents and inherited genetic backgrounds. The determination of how pulmonary fibrosis will evolve remains difficult because different patients experience widely diverse rates of lung function loss. Forced Vital Capacity represents a crucial lung functioning parameter which doctors use to track disease progression although its deterioration patterns are hard to predict.
Chronic progressive interstitial lung disease pulmonary fibrosis damages the lung permanently, impairing normal lung function and ultimately resulting in mortality. As of right now, PF cannot be healed and its pathophysiology must be identified. Therefore, the main goal of treating this illness is to manage and slow down the progression and development of PF in order to extend patients' lives. An earlier diagnosis and early interventional treatment are crucial for disorders like PF in order to extend the survival period of PF patients. A prompt and precise PF diagnosis is therefore essential. The clinical diagnosis of PF includes imaging, tissue biopsy, and lung function tests. Lung imaging methods' ability to accurately diagnose PF depends on the relevant precision of the radiology imaging equipment.
Furthermore, when implementing imaging modalities to diagnose PF, the radiologist's and the doctors' experience and knowledge are also limiting considerations. The diagnosis of this condition varies among pulmonologists, even for the same cases. One of the most common and economical medical imaging tests used in clinical practice is the chest X-ray, which is used to diagnose PF. In severe situations, computed tomography (CT) performs a number of body scans that are combined to create a three-dimensional X-ray image that can be examined using a computer to validate the diagnosis made from X-ray images. When lung disorders like PF develop quickly, many CT scans are necessary. 
As a result, CT scans are very expensive, time-consuming, and perhaps hazardous to the patient due to their radiation use. An artificial intelligence-based decision system that can quickly and accurately classify and diagnose PF is therefore needed for diagnostic purposes. Predicting the degree of a patient's lung function decline from a CT scan of their lungs is the goal of the current goal. The results of a spirometer, which gauges the forced vital capacity (FVC), or the amount of air breathed, are used to evaluate lung function. A baseline chest CT scan and related clinical data for a group of patients are included in the dataset. The patient's FVC is measured after multiple follow-up visits over a period of around 1-2 years, following the acquisition of a picture at time Week = 0.
The artificial neural network type known as autoencoder performs unsupervised learning to accomplish dimensionality reduction together with feature extraction and data reconstruction tasks. The autoencoder employs an encoder phase that reduces input data into a condensed latent space and a decoder mechanism that regenerates the initial input from this compressed format. The widespread usage of autoencoders occurs in data processing applications which manage high-dimensional data efficiently including medical imaging together with anomaly detection and noise reduction operations. 

## Features
## Neural Network Architecture:
The model is a combination of convolutional autoencoders (for CT scans) and a dense autoencoder (for clinical data), followed by a fusion network for final prediction.
## Image-Based Autoencoder (for CT Scans):
- Uses CNN-based autoencoder to extract lung fibrosis features from HRCT scans.
- The encoder compresses the high-dimensional image into a smaller latent space.
- The decoder reconstructs the original image (used only during training).
## Autoencoder Architecture: 
Autoencoder Architecture serves as the fundamental element in the method because it uses neural networks for building unsupervised learning systems. 
The system combines an encoder which transforms the input data into latent space with fewer dimensions followed by a decoder to rebuild original input data from the compressed data. 
The autoencoder develops representations for pulmonary fibrosis features through clinical measurements as well as lung function data points that highlight relevant disease patterns.
## Convolutional Autoencoders (CAE):
Convolutional Autoencoders (CAE) represent an excellent option because they extract spatial patterns better than fully connected layers specifically for imaging data including CT scans.
## Variational Autoencoders (VAE):
Considerable data distribution modeling along with better latent representation smoothing can emerge from the addition of probabilistic layers in Variational Autoencoders (VAE) that helps enhance prediction accuracy.

Dimensionality Reduction – Compressing high-dimensional CT scan data into meaningful latent representations.
Feature Extraction – Learning hidden patterns in structured data (e.g., FVC trends, demographic features).
Anomaly Detection – Identifying abnormal lung patterns that indicate severe fibrosis progression.

## Requirements
<!--List the requirements of the project as shown below-->
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding the sign language detection system.
* Deep Learning Frameworks: TensorFlow for model training, MediaPipe for hand gesture recognition.
* Image Processing Libraries: OpenCV is essential for efficient image processing and real-time hand gesture recognition.
* Version Control: Implementation of Git for collaborative development and effective code management.
* IDE: Use of VSCode as the Integrated Development Environment for coding, debugging, and version control integration.
* Additional Dependencies: Includes scikit-learn, TensorFlow (versions 2.4.1), TensorFlow GPU, OpenCV, and Mediapipe for deep learning tasks.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

<img width="97" alt="image" src="https://github.com/user-attachments/assets/de7af4db-72c3-4338-995d-ad40d3a2ca85" />



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)

Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
The Sign Language Detection System enhances accessibility for individuals with hearing and speech impairments, providing a valuable tool for inclusive communication. The project's integration of computer vision and deep learning showcases its potential for intuitive and interactive human-computer interaction.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
1. N. S. Gupta, S. K. Rout, S. Barik, R. R. Kalangi, and B. Swampa, “Enhancing Heart Disease Prediction Accuracy Through Hybrid Machine Learning Methods ”, EAI Endorsed Trans IoT, vol. 10, Mar. 2024.
2. A. A. BIN ZAINUDDIN, “Enhancing IoT Security: A Synergy of Machine Learning, Artificial Intelligence, and Blockchain”, Data Science Insights, vol. 2, no. 1, Feb. 2024.





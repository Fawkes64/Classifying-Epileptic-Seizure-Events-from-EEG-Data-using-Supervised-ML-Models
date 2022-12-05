# Classifying-Epileptic-Seizure-Events-from-EEG-Data-using-Supervised-ML-Models
EE502 Class Project

This repository holds a copy of the Pre-Processed CHB MIT EEG Dataset along with MATLAB code describing an ML pipeline used to attempt to perform seizure event classification on the dataset. To use this code and data, ensure in line 11 of the MATLAB code to properly put the directory you have the unzipped dataset file structure in. In addition, I fully encourage you to ensure you are using MATLAB 2022B or newer as this was developed upon this version and only tested on this version of MATLAB.

The Pre-Processed CHB MIT EEG Dataset can be obtained from the following link: "https://ieee-dataport.org/open-access/preprocessed-chb-mit-scalp-eeg-database"
Once the dataset is downloaded and unzipped, the folder structure should match the that of which is in the the MATLAB code, allowing for easy access of the data files for the pipeline.

As an alternative the feature set table can be loaded into MATLAB and sections of the code for feature selection and classification performed without the inital parsing, processing and feature extraction.

References for this work:
[1]	B. Deepa and K. Ramesh, “Epileptic seizure detection using deep learning through min max scaler normalization,” Int. J. Health Sci., pp. 10981–10996, May 2022, doi: 10.53730/ijhs.v6nS1.7801.
[2]	A. H. Shoeb, “Application of machine learning to epileptic seizure onset detection and treatment,” Thesis, Massachusetts Institute of Technology, 2009. Accessed: Sep. 23, 2022. [Online]. Available: https://dspace.mit.edu/handle/1721.1/54669
[3]	A. Morley and L. Hill, “10-20 system EEG Placement,” p. 34.
[4]	A. A. Ein Shoka, M. H. Alkinani, A. S. El-Sherbeny, A. El-Sayed, and M. M. Dessouky, “Automated seizure diagnosis system based on feature extraction and channel selection using EEG signals,” Brain Inform., vol. 8, no. 1, p. 1, Feb. 2021, doi: 10.1186/s40708-021-00123-7.
[5]	S. E. Sánchez-Hernández, R. A. Salido-Ruiz, S. Torres-Ramos, and I. Román-Godínez, “Evaluation of Feature Selection Methods for Classification of Epileptic Seizure EEG Signals,” Sensors, vol. 22, no. 8, p. 3066, Apr. 2022, doi: 10.3390/s22083066.
[6]	A. Shoeb, “CHB-MIT Scalp EEG Database.” physionet.org, 2010. doi: 10.13026/C2K01R.
[7]	I. Stancin, M. Cifrek, and A. Jovic, “A Review of EEG Signal Features and Their Application in Driver Drowsiness Detection Systems,” Sensors, vol. 21, no. 11, p. 3786, May 2021, doi: 10.3390/s21113786.


# Classifying-Epileptic-Seizure-Events-from-EEG-Data-using-Supervised-ML-Models
EE502 Class Project

This repository holds a copy of the Pre-Processed CHB MIT EEG Dataset along with MATLAB code describing an ML pipeline used to attempt to perform seizure event classification on the dataset. To use this code and data, ensure in line 11 of the MATLAB code to properly put the directory you have the unzipped dataset file structure in. In addition, I fully encourage you to ensure you are using MATLAB 2022B or newer as this was developed upon this version and only tested on this version of MATLAB.

The Pre-Processed CHB MIT EEG Dataset can be obtained from the following link: "https://ieee-dataport.org/open-access/preprocessed-chb-mit-scalp-eeg-database"
Once the dataset is downloaded and unzipped, the folder structure should match the that of which is in the the MATLAB code, allowing for easy access of the data files for the pipeline.

As an alternative the feature set table can be loaded into MATLAB and sections of the code for feature selection and classification performed without the inital parsing, processing and feature extraction.

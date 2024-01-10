# ECG-data-augmentation
This repository consisted of the files related to a research paper on ECG data augmentation method.

Pre-Processing:

- The 12-lead ECG signals must be in numpy array i.e., 12 columns x 1000 rows. The WFDB library is useful for this task, when signals are downloaded from physioNet.org

For ECG augmentation:

- Open the Data Augmentation algorithm notebook and change the dataset path / output directory and input the necessary parameters in main function.

For Model Training:

- Open the customized CNN architecture or Transfer learning models folder and change the dataset path and play run button. It will train the model and will save output model inside the dataset directory.


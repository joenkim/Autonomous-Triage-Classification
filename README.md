# Autonomous-Triage-Classification


"Hospital Triage Dataset" Folder contains the model trained on the dataset from https://www.kaggle.com/datasets/maalona/hospital-triage-and-patient-history-data?resource=download , which has been pre-processed and stored as "pre-processed.csv". "data_processing.ipynb" contains the model that was trained. "visualization.ipynb" contains graphs on the dataset's inputs.


"Patient Priority Dataset" Folder contains the dataset "og6K.csv" and "raw_prep_6k.csv" that wer used for training the model. "triage_6k_v2.ipynb" contains the model that was trained only on the "og6k.csv" dataset, whereas "combined.ipynb" trains a model on a combined dataset of "og6k.csv" and "pre-processed.csv".


"ECG Image Dataset" Folder contains the Convolutional Neural Network Model trained on ECG images dataset from https://www.kaggle.com/datasets/erhmrai/ecg-image-data . To load the model and weights, download the saved CNN model and weights from https://drive.google.com/file/d/1fZRF8TwlCTwuGSnxXmDZ5f_FMTvAar2n/view?usp=share_link (ECG-model.pth), add the file to ECG Image Dataset folder and run the "ECG_cnn.ipynb" notebook.

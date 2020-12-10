# Artificial_Intelligence_Doctor
AI Doctor is a project which involves machine learning models to predict the clinical events which can help the doctors as well as the patients.

This project is divided into three parts
1) Dataset preprocessing
2) Training
3) Testing

Steps involved in the project.
1) At first, 'dataset.py' should be executed. This file is for preparing the datset for the model. CSV files will be read from the MIMIC dataset folder and it implements some pre-processing for dataset and save the files as train, validation and test which will be saved in data folder.

2) Next 'train_model.py' file should be executed. This files implements the model, set the parameters and the loss function and it also reads the training data.

3) At last, 'test_model.py' file should be executed.This file loads the dataset and the trained models from experiments folder to test the model. An accuracy metric Recall will be fecthed. 

Execution procedures and the results acheived are shown in 'results.txt' file.





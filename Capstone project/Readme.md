# Capstone-Project
CT scan image classification using Resnet 50 architecture
Download the dataset from here:

https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset or https://drive.google.com/drive/folders/1WOeodRmv1Mw5Cswuip3nUIi6ViQWKpo_?usp=sharing

This dataset contains 1252 CT scans that are positive for SARS-CoV-2 infection (COVID-19) and 1230 CT scans for patients non-infected by SARS-CoV-2, 2482 CT scans in total. These data have been collected from real patients in hospitals from Sao Paulo, Brazil. The aim of this dataset is to encourage the research and development of artificial intelligent methods which are able to identify if a person is infected by SARS-CoV-2 through the analysis of his/her CT scans

Install and import all the necessary libraries to run the program

If you dont have GPU in your system, for better experience you can use kaggle or google colab because they provide GPU runtime so that training can be done faster

OUTPUT

Accuracy and loss

![model loss](https://user-images.githubusercontent.com/99254412/195312763-1a357f53-a72f-4248-973c-2d190530153f.png)

![model acc](https://user-images.githubusercontent.com/99254412/195312827-24feffcf-2eaf-4bb7-82a9-f2afa75e663c.png)


CONFUSION MATRIX

![Cm](https://user-images.githubusercontent.com/99254412/195312937-a8149740-a2aa-4dd9-8940-53f5c93d8a23.png)


PREDICTION

![predicted](https://user-images.githubusercontent.com/99254412/195312994-76c9bf1a-58e1-45e9-9c0d-15fcd42f9301.png)



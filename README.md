# CT_covid_detection_pyTorch
CNN for COVID-19 detection in CT images using pyTorch

The aim of the following project is to train a convolutional neural network to detect 
clinical signs of COVID-19 from chest CT scan images. 
CT and other chest imaging techniques have proven to be instrumental in helping 
practitioners to diagnose the disease during the outbreak of COVID-19. 

The folders CT_COVID and CT_NonCOVID contains the COVID-CT dataset used in the 
present project.The dataset was created by Zhao et al. (2020) and it is organized 
in two folders:

The CT_COVID folder contains 349 chest CT images depicting clinical findings of COVID-19 
from 216 patients.

The CT_NonCOVID folder contains a set of 397 chest CT negative CT scans that are normal 
or contain other types of diseases. CT negative images were collected from different 
databases, including: MedPix database (open access database ofd medical images), 
the LUNA dataset (lung cancer database), 
the Radiopaedia website (radiology images from patient cases) and PubMed Central.

References: Zhao, Jinyu and Zhang, Yichen and He, Xuehai and Xie, Pengtao (2020). 
COVID-CT-Dataset: a CT scan dataset about COVID-19. arXiv preprint. arXiv:2003.13865

The "models" folder contains the best performing convolutional neural networks 
trained used Google Colaboratory and pyTorch.

The file "CT_covid_detection_model.ipynb" is the notebook used for model training and
evaluation in Google Colaboratory. A .pdf version of the notebook is also present 
in the main folder.

fr 2021-01-20

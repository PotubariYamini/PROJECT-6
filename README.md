Corona Lung-CNN

![image](https://user-images.githubusercontent.com/111189874/189468717-3b8c8e2b-64b0-47fc-89fd-61d58820863f.png)

1. About the dataset:
The virus called the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) had been discovered in late 2019. The virus which originated in China became a cause of a disease known as Corona Virus Disease 2019 or COVID-19. The World Health Organization (WHO) declared the disease as a pandemic in March 2020 . According to the reports issued and updated by global healthcare authorities and state governments, the pandemic affected millions of people globally. The most serious illness caused by COVID-19 is related to the lungs such as pneumonia. The symptoms of the disease can vary and include dyspnea, high fever, runny nose, and cough. These cases can most commonly be diagnosed using chest X-ray imaging analysis for the abnormalities.


2. Requirements:
* python
* jupyter notebook
* pandas
* numpy
* tensorflow keras, sklearn libraries
* matplolib

3. Workflow:
![6621607 fig 001](https://user-images.githubusercontent.com/111189874/189468860-a9e87b3a-0839-47df-858c-a10c5a97fee6.png)

4. Dataset Preprocessing:
* Balancing Dataset Classes:
To balance the given dataset, in order to improve the performance of the proposed CNN models in the detection of COVID-19 cases, 136 normal chest X-ray images have been used. These concatenated extra X-ray images were downloaded from Kaggle [22]. After balancing the dataset when the models have been trained again on the resulted dataset, the accuracy of the given CNN models was improved to 69%. Still, the performance given by the models in terms of accuracy and other measures was not justified as an effective system for COVID-19 detection.

5. Building the model:
* by using tensorflow keras we build the model.
* CNN model:

![6621607 fig 004](https://user-images.githubusercontent.com/111189874/189469024-cc503117-85b9-4bfe-bb4e-8581fe187f9f.png)


* Model accurary :

![image](https://user-images.githubusercontent.com/111189874/189469318-0f27689a-2569-433d-9524-ccce4b5e1edb.png)


* model loss :

![image](https://user-images.githubusercontent.com/111189874/189469361-d1e2ebb3-3341-43b8-ab5f-54515347c65a.png)











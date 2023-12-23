Dataset source: https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education

The purpose of the experiment is finding the best classification model out of 4: Logistic Regression, Decision Jungle, Decision Forest and Neural Networks, and deploying said model as a web service end point.

![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0001.jpg)

The models will predict students' adaptability level to online classes (low, moderate, high) based on their education level, age, internet type, network type etc. 
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0002.jpg)
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0003.jpg)


![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0004.jpg)

Assumably,  the "IT Student" column is less relevant, so it has been removed.
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0005.jpg)


![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0006.jpg)
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0007.jpg)
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0008.jpg)
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0009.jpg)

The following slides display the 4 models' results:
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0010.jpg)
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0011.jpg)
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0012.jpg)
The Neural Network model proved to have the best accuracy and precision:
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0013.jpg)

The model is deployed and accessed through API calls with Postman. 
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0014.jpg)
Based on the chosen inputs, the model predicted that the student's adaptability is moderate. The "IT Student" input is not taken into account  by the model.
![alt text](https://github.com/StegarescuAnaMaria/Classification_Model_with_Azure_ML/blob/main/images/0015.jpg)

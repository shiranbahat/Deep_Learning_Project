# Deep Learning Project

classifiaction of blood cell subtypes using deep learning

Data was taken from Kaggle (https://www.kaggle.com/paultimothymooney/blood-cells) and contains 12,500 augmented images of blood cells from 4 types:

![image](https://user-images.githubusercontent.com/60502982/111831523-2fca8300-88f8-11eb-9c89-2eb501bf5d30.png)


The notebook present three main models: ResNet50, Inception V3 and Vgg16 used to predict the blood cell types 

![image](https://user-images.githubusercontent.com/60502982/111832605-b59afe00-88f9-11eb-919a-e4ae545279de.png)

to a final accuracy score of 1.0

![image](https://user-images.githubusercontent.com/60502982/111832139-1118bc00-88f9-11eb-9e89-3a0125f3de93.png)


The project consists of base models, but also of models using image segmentation method masking the surrounding red blood cells:


![image](https://user-images.githubusercontent.com/60502982/111832498-8c7a6d80-88f9-11eb-800c-1e5f76a7ec6b.png)


Cross validation function was added to validate the results:

![image](https://user-images.githubusercontent.com/60502982/111833084-4d98e780-88fa-11eb-9150-a6b2cf1bda60.png)

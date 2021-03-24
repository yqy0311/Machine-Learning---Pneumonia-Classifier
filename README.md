# Machine-Learning---Pneumonia-Classifier

# X-ray Diagnosis on Bacterial and Viral Pneumonia

With our healthcare system heavily impacted by the current COVID-19 situation, the team sees an opportunity to help relieve the workload and stress for doctors and radiologists, and we came up with this project to develop an ML model that reads chest x-rays and diagnoses the presence of different types of pneumonia. This could potentially allow patients to self-diagnose and doctors to speed up their early-stage pneumonia x-ray diagnosis process. Pneumonia can be caused by bacteria, fungi, and viruses. In this project, we will be mainly exploring bacterial and viral pneumonia.


The team used 5856 chest x-ray images provided by Kaggle, available at https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia. The images are organized in three folders (training, validation, and testing), and have two subfolders for each folder (normal and pneumonia). The team re-splited the images as 70% training data, 15% validation data, and 15% testing data.

The team created two prototypes, “CNN from scratch” and transfer learning. We trained and tuned the two models separately on the same training and validation dataset and after comparing the two models, we decided to move forward with the “CNN from scratch” model since it achieved a higher validation accuracy.

![image](https://user-images.githubusercontent.com/26075877/112363947-030bd680-8d11-11eb-9b5b-c661f31fe272.png)

![image](https://user-images.githubusercontent.com/26075877/112364314-57af5180-8d11-11eb-874e-26bc79d72b7f.png)



Our NP model can classify normal and pneumonia classes with a test accuracy of 92.8%. It also correctly predicts 4 out of 4 chest x-ray images when we test it on a new Normal vs Pneumonia dataset. The test accuracy of the bacterial VS virus pneumonia model achieved an overall accuracy of 75.5%.

![image](https://user-images.githubusercontent.com/26075877/112371986-3010b700-8d1a-11eb-80f4-9840ad207327.png)

![image](https://user-images.githubusercontent.com/26075877/112372012-3737c500-8d1a-11eb-8c59-e1b831a7d5c4.png)


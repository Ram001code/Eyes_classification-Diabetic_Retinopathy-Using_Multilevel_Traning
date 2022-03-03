# Eyes_classification(Diabetic_Retinopathy)_Using_Multilevel_Traning
Eyes classification using muti-level training and using Transfter learning. 

Perform EDA on the dataset (Without EDA we were not getting any good result)

Stored train and test data with labels after doing preprocessing

Above(2-4) steps were done in local machine. 

Model training was performed on Google-Colab. 

Used flow_from_dataframe for data augmentation.

Used Transfer learning model Resnet50(You can try with different models)

Pre-training: Initial training was performed in 5 layers of Resnet only and for 2 epocs. Just to warm up the model. 

Post-training: Then all the layers were used for training and ReduceLROnPlateau was to stablize and reduce the learning rate by DECAY_DROP(0.5) factor once loss will reach min. 

pre and post training of the model

ALso calculated Cohen-cappa of the model.

Datasets: https://www.kaggle.com/mariaherrerot/aptos2019


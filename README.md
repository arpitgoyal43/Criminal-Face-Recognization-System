# Criminal Face Recognition System
We have made a python script to recognize multiple faces at a same time.This Recognition system can be implemented into the **Security System** to detect the criminal face. This system can be used in **Atm cameras** and **Street cameras** to detect the criminal, if the face of the criminal is in the database of Police Department.

If a criminal gets arrested, criminal's data is updated to the police database. A dataset of criminal's face(about 100 photos) is created which will help the department for future recognition. We have created a Machine Learning model using **_OpenCv_** and **_LBPH_** algorithm to train the dataSet of criminal's face. 
## There are mainly three python scripts which run in a sequence:
1) **_datasetCreater_** - It will create the dataset of your face by taking some sample photos.
2) **_trainer_** - It will train the sample dataset. 
3) **_detector_** - It will detect your face according to the face trained.

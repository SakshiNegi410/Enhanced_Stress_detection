# Enhanced_Stress_detection
SCREENSHOTS
![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/38e50fbf-e247-426b-b975-bdb1a2291670)

![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/38bae4b3-0453-4955-80fe-79f84a15e2d5)

![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/55023672-9538-4800-a152-b00d191dfeea)

![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/57549d21-24f7-4188-826a-1794800c2291)


![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/23505747-b233-4b13-9c08-e909f3351ed4)

![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/25fa6cba-7504-4823-9ab4-48e18e75a777)
The proposed System Machine Learning algorithms like KNN classifiers are applied to classify stress. Image Processing is used at the initial stage for detection, the employee’s image is given by the browser which serves as input. In order to get an enhanced image or to extract some useful information from it image processing is used by converting image into digital form and performing some operations on it. By taking input as an image and output may be image or characteristics associated with that images. The
emotion are displayed on the rounder box. The stress level indicating by Angry, Disgusted, Fearful, Sad. Here we do three different ways to predict stress level . Text based detection where we used decision tree algorithm , Image based detection which is based on KNN and another using Live Cam detection using python opencv.

ADVANTAGES OF PROPOSED SYSTEM:
	Output in which result is altered image or report that is based on image analysis. 
	Stress Detection System enables employees with coping up with their issues leading to stress by preventative stress management solutions. 
	We will capture images of the employee based on the regular intervals and then the tradition survey forms will be given to the employees 
	Algorithm: K-Nearest Neighbor (KNN) for Image data
	Algorithm: Decision Tree for text data
	Customized Algorithm : Detection through web came using openCV

4SYSTEMARCHITECTURE

 ![image](https://github.com/SakshiNegi410/Enhanced_Stress_detection/assets/125671478/d4a7d894-114a-4738-ab06-1275fef29b91)


4.1 IMPLEMENTATION

MODULES: 
•	User 
•	Admin 
•	Data Preprocess 
•	Machine Learning
MODULES DESCRIPTION:
User:
The User can register the first. While registering he required a valid user email and mobile for further communications. Once the user register then admin can activate the customer. Once admin activated the customer then user can login into our system. First user has to give the input as image to the system. The python library will extract the features and appropriate emotion of the image. If given image contain more than one faces also possible to detect. The stress level we are going to indicate by facial expression like sad, angry etc.. The image processing completed the we are going to start the live stream. In the live stream also we can get the facial expression more that one persons also. Compare to tensorlflow live stream the tesnorflow live stream will fast and better results. Once done the we are loading the dataset to perform the knn classification accuracy precession scores. .
Admin:
Admin can login with his credentials. Once he login he can activate the users. The activated user only login in our applications. The admin can set the training and testing data for the project dynamically to the code. The admin can view all users detected results in hid frame. By clicking an hyperlink in the screen he can detect the emotions of the images. The admin can also view the knn classification detected results. The dataset in the excel format. By authorized persons we can increase the dataset size according the imaginary values.
Data Preprocess:
Dataset contains grid view of already stored dataset consisting numerous properties, by Property Extraction newly designed dataset appears which contains only numerical input variables as a result of Principal Component Analysis feature selection transforming to 6 principal components which are Condition (No stress, Time pressure, Interruption), Stress, Physical Demand, Performance and Frustration. 
Machine Learning: 
K-Nearest Neighbor (KNN) is used for classification as well as regression analysis. It is a supervised learning algorithm which is used for predicting if a person needs treatment or not. KNN classifies the dependent variable based on how similar it is; independent variables are to a similar instance from the already known data. the Knn Classification can be called as a statistical model that uses a binary dependent variable. Inclassification analysis, KNN is estimating the parameters of a KNN model. Mathematically, a binary KNN model has a dependent variable with two possible value, which is represented by an indicator variable, where the two values are labeled "0" and "1".




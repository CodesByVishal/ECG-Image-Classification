# Detection-of-Cardiovascular-Disease-using-ECG-Images-with-deepLearning-Methods
# ABSTRACT
Cardiovascular diseases (heart diseases) are the leading cause of death worldwide. The earlier they can be predicted and classified; the more lives can be saved. Electrocardiogram (ECG) is a common, inexpensive, and non-invasive tool for measuring the electrical activity of the heart and is used to detect cardiovascular disease. In this project, the power of deep learning techniques was used to predict the four major cardiac abnormalities: abnormal heartbeat, myocardial infarction, history of myocardial infarction, and normal person classes using the public ECG images dataset of cardiac patients.
The aim is to improve early detection and classification of cardiovascular diseases, which are a leading cause of death globally. The project proposes a convolutional neural network (CNN) architecture for this purpose. The study compares the performance of the CNN model with existing works, getting superior results in terms of accuracy, recall, precision, and F1 score. Additionally, the CNN model is used for feature extraction in conjunction with traditional machine learning algorithms such as support vector machine, K-nearest neighbours, and logistic regression, with promising outcomes.
Furthermore, utilization of XGBoost, an optimized distributed gradient boosting library, to enhance the predictive capabilities of the model. XGBoost is highlighted for its efficiency and scalability in training machine learning models, making it a valuable tool for ensemble learning and improving prediction accuracy.In this project, Streamlit, a popular open-source Python library for building interactive web applications, is integrated to create a user-friendly interface for interacting with the predictive model.

# ***DATA SET LINK***
 ECG images: https://data.mendeley.com/datasets/gwbz3fsgp8/2 
 
The above dataset contains ECG image signals from both healthy individuals and persons with cardiovascular problems.
The dataset contains 4 categories of ECG images:
1.Normal Person ECG Images (284x12=3408)
2. ECG Images of Myocardial Infarction Patients (240x12=2880)
3. ECG Images of Patient that have abnormal heartbeat
   (233x12=2796)
4. ECG Images of Patient that have History of MI (172x12=2064).
(Total Images of data set= 11,148)




# **Approach**
The user uploads an ECG image to our web app. Then, we use techniques like rgb2gray conversion, gaussian filtering, resizing, and thresholding to extract only the signals that do not have grid lines. The required waves (P, QRS, T) are then extracted using contour techniques and converted to a 1D signal. The normalized 1D signal is then fed into our pre-trained ML model, which is then analyzed. When the model has completed the analysis, it returns the results to the user based on the findings.

Here, we have used 4 categories for image classification for our ECG images.
Normal Person ECG Images
Myocardial Infarction Patients
Patient that have abnormal heartbeat
Patient that have History of Myocardial Infarction




![329467771-de0888bb-cf13-4716-b531-579125089f6e](https://github.com/CodesByVishal/ECG-Image-Classification/assets/163639829/f9f798e5-c549-4601-a4ff-6e34ef54b034)




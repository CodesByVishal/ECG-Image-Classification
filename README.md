### Detection of Cardiovascular Disease using ECG Images with Deep Learning Methods

#### Abstract
Cardiovascular diseases (CVDs) are a leading global cause of mortality, emphasizing the critical need for early detection and classification. This project leverages deep learning techniques to predict major cardiac abnormalities—abnormal heartbeat, myocardial infarction (MI), history of MI, and normal classes—from a publicly available dataset of ECG images.

#### Key Features
- Developed deep learning models achieving superior performance in accuracy, recall, precision, and F1 score compared to existing methods.
- Integrated Streamlit for a user-friendly interface, facilitating real-time interaction with predictive models.
- Utilized a dataset of 11,148 categorized ECG images to enhance early detection and classification of heart conditions.

#### Technologies Used
Colab, Streamlit, Localtunnel  
Libraries: Skimage, matplotlib, NumPy, Scipy.nd_image, Pandas, SkLearn, joblib, XGBoost, Ensemble, Pickle  

#### Machine Learning Algorithms
1. K-Nearest Neighbour (KNN)
2. Logistic Regression
3. Support Vector Machine (SVM)
4. XGBoost
5. Voting Based Ensemble Classifier with GridSearchCV

#### Dataset
ECG images: [Dataset Link](https://data.mendeley.com/datasets/gwbz3fsgp8/2)  
Categories:
1. Normal Person ECG Images: 3408
2. ECG Images of Myocardial Infarction Patients: 2880
3. ECG Images of Patients with Abnormal Heartbeat: 2796
4. ECG Images of Patients with History of MI: 2064

#### Project Workflow
- ECG images undergo preprocessing (e.g., rgb2gray, gaussian filtering, resizing) to extract relevant signals.
- Contour techniques are used to isolate waves (P, QRS, T), converted into normalized 1D signals.
- Models trained on preprocessed data for accurate classification and prediction.
- Real-time feedback provided through an intuitive UI powered by Streamlit.

#### Conclusion
The application of deep learning in ECG-based CVD detection signifies transformative potential for cardiac care, promising enhanced patient outcomes through early intervention.

---

This README provides an overview of the project, highlighting its objectives, methodologies, and technological implementations, aiming to support future development and collaboration in cardiovascular health research.

<b>PROJECT 2

Diabetes Prediction using Machine Learning using Python</b>

<b>Problem Statement</b>

Building a Machine Learning System that can predict whether the person as Diabetes or not. 

<b>Support Vector Machine</b>

Support Vector Machine are powerful yet flexible supervised ML Algorithm used both for classification and regression. But are usually used for classification problems. This algorithm is extremely popular for their ability to handle multiple continuous and categorical variables.
An SVM model is basically a representation of different classes in a hyperplane in multidimensional space. The hyperplane will be generated in an iterative manner by SVM so that the error can be minimized.The goal of SVM is to divide the datasets into classes to find a maximum marginal hyperplane (MMH).

Support Vectors − Datapoints that are closest to the hyperplane is called support vectors. Separating line will be defined with the help of these data points.

Hyperplane − As we can see in the diagram, it is a decision plane or space which is divided between a set of objects having different classes.

Margin − It may be defined as the gap between two lines on the closet data points of different classes. It can be calculated as the perpendicular distance from the line to the support vectors. Large margin is considered as a good margin and small margin is considered as a bad margin.

The main goal of SVM is to divide the datasets into classes to find a maximum marginal hyperplane (MMH) and it can be done in the following two steps −

•	First, SVM will generate hyperplanes iteratively that segregates the classes in best way.

•	Then, it will choose the hyperplane that separates the classes correctly.
 
![SVM](https://user-images.githubusercontent.com/55580071/166748938-674da49e-1872-4d38-9566-28714aefd55a.JPG)

<b>Algorithm</b>

The data is fed to the machine learning model. The model learns from data and the respective labels. The model is trained with different medical details such as BMI, Blood Glucose Level, Insulin Level and also if the patient has diabetes or not. These act as labels to predict whether the person is diabetic or non-diabetic. 
Once the data is fed to Support Vector Machine, it tries to plot the data. Form the plot hyperplane is found. The Hyperplane separates data into two sets. Therefore, when new data is trained, the Support Vector Machine adds the data into either of these set. By this separation, the prediction of whether the patient is diabetic or non-diabetic can be made. 

<b>Work Flow</b>

Diabetes data to be obtained and trained to the model. 

Data Pre-processing: The data is analysed in this step. The raw data will be not suitable to feed into machine learning model. The data needs to be standardized as there are lot of attributes pertaining to medical information, and the resulting data will be brought to same range.

Train Test Split: The dataset is split into Training data and test data. The machine learning model is trained with Training data and the accuracy score of the model is found by the help of test data. The accuracy score represents the performance of the model. 

Support Vector Machine Classifier: Once the data is split to training and test data, it is fed to Support vector machine model. The classifier model classifies whether the patient is diabetic or non-diabetic.

Trained Support Vector Machine Classifier: Obtained after training the model with data. This classifier now predicts the presence of diabetes. 
 
![Work FLow](https://user-images.githubusercontent.com/55580071/166748963-752d61a9-7465-48d9-92e7-306ec74c740a.JPG)


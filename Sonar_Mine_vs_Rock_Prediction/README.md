<b>SONAR Rock vs Mine Prediction</b>

<b>Problem Statement:</b> Considering there is a war going on between two countries under water, there are submarines. The enemy country has planted mines underwater. The mines explode when any object comes in contact with it. But there can also be Rocks in the ocean. The submarines need to predict whether it is crossing a mine or rock. The problem is the predict whether the object beneath the submarine is a mine or a rock.

<b>Solution</b> Submarines sends sounds signals and receives it back. These sounds are used to detect whether the object is a mine or just a rock in the ocean.

<b>Work Flow</b>

•	Collect the sonar data: In the laboratory setup, an experiment can be done where sonar is used to bounce back from metal cylinders and rock. Because the mines are made of metals. We collect this sonar data obtained from metal cylinder and rocks. Sonar data is fed to the machine learning model. The model then predicts whether the object is rock or mine.

•	Data Pre-processing: Data needs to be analysed.

•	Train Test Split: We split the data into training and test data set because if there are 100 records, we train our model with 90 data instances and test our model the remaining 10 data points. 

•	Logistic Regression Model: After splitting the data into train and test set, we feed the data to the machine learning model. Logistic Regression model is used as it works well with binary classification problem. This is because as stated in our problem statement we are predicting whether the object is rock or mine. It is to remember that this is a supervised learning algorithm. 

•	Trained Logistic Regression Model: This model is obtained after training the model. This model would have learnt to how to differentiate a rock and mine based on sonar data.


 
![WorkFlow](https://user-images.githubusercontent.com/55580071/166698778-55d22c37-a1fe-4965-a5a9-0a7b2ad17b51.JPG)


# EMPLOYEE-CHURN-PREDICTION
  Employee churn prediction is a machine learning model uses linear regression to predict the employees decision on leaving company.
  
# PROJECT DESCRIPTION
  By updating the entire status of each employee database, we predict his decision accordingly. So that one could predict what the employee is going to do in future. If he is going to continue his work or he demand salary increment. By using this data the Manager could decide about the employee and could properly utilize the Human Resource.
 # AZURE SERVICES USED:
   Azure machine learning studio is used to create, train and evaluate the machine learning model.
   In Azure machine learning portal, select or import a dataset for the model. 
   After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks.
   The final output will be visualized in the evaluated model.
  
 # EMPLOYEE CHURN PREDICTION MACHINE LEARNING MODEL:  
![EMPLOYEECHURNPREDICTION-ML](https://user-images.githubusercontent.com/67775117/152033614-80a46737-2ff9-462c-94e8-e76dd0028cca.png)

 # EMPLOYEE CHURN PREDICTION DATASET:
![CHURN-PREDICTION-DATASET](https://user-images.githubusercontent.com/67775117/152033629-68dcca35-505a-4449-9c5d-dcb9deee9ee1.png)

 # TRAINED MODEL:
![CHURN-PREDICTION-TRAINED-MODEL](https://user-images.githubusercontent.com/67775117/152033634-180e3772-ba67-4e2d-b12a-2c1f116c8394.png)

 # EVALUATION MODEL:
![CHURN-PREDICTION-EVALUATION-MODEL](https://user-images.githubusercontent.com/67775117/152033644-5e12dde5-41bc-4a99-bbbd-cd1191f7050d.png)


 # DETAILED DESCRIPTION:
 
Create Project/Experiment and import HR data set from local file system. 
After creating experiment, we need to drag and drop the required modules in canvas.

I have used the below modules for my experiment in the given order:

    Data set: 
	Data set required for experiment is added
    Editing Metadata:
	Used to change data type of fields, etc.
    Splitting data: 
	Split the data for training and evaluation.
    Two-class Decision forest:
	 Classification algorithm is used for training a model. 
	The output values is 0 or 1. Two class Decision forest gives the accurate and quick results. 
	0 - Employee will not leave the company.
	1 - Employee will leave the company.
	
    Model Training: Algorithm and the training data set are the input given for the model training.
    Score model: Score model provide the output by adding two more columns. We can visualize the datasets by clicking visualize.
    Evaluate model: This will give the accuracy, matrix values. The model gives an accuracy of 96.9% and precision of 93.6%.

    Permutation feature: responsible for the correct output.

    After creating, run the model by clicking run button in the bottom side. After running successfully, we can score and evaluate the model.

2. Deploying the model:

Deploy the model by Setting up Web Service in ML Studio. For first time select Update Predictive Experiment.
after deployment of model, it can be used in webs.

Web Service Consumption options:

    Excel 2010 or earlier
    Request-Response Web App Template


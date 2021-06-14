# Project overview
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc)
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/titanic%20image.jpg">


# Code and Resources
- Libraries are required:`numpy`,`Pandas`, `Matplotlib`, `seaborn`,`sklearn`
- Data model: `Random Forest`,`GaussianNB`,`Logistic Regression`,`KNN`,`SVC`,`Xgboost`,
- Data validation:`GridSearchCV`,`RandomizedCV`
- Saving the model: using `pickle`


# Data Cleaning
**Varaible Descriptions**
- Pclass  --> Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- survival --> Survival (0 = No; 1 = Yes)
- name     --> Name
- sex      --> Sex
- age      --> Age
- sibsp    --> Number of Siblings/Spouses Aboard
- parch    --> Number of Parents/Children Aboard
- ticket   --> Ticket Number
- fare     --> Passenger Fare (British pound)
- cabin    --> Cabin
- embarked --> Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
- boat     --> Lifeboat
- body     --> Body Identification Number
- home     --> .dest Home/Destination

**Missing Values**
- These are missing values in train data set
<img src ="https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/data%20set.PNG">

# Exploratory data analysis

<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/1.PNG">
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/2.PNG">
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/3.PNG">
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/4.PNG">

# Model Building
- LogisticRegression
- GaussianNB
- KNN
- RandomForest
- SVC
- XBG
# Model Performance
The best model is SVC

# Deployment
 - Flask Frame Work

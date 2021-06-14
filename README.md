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
- These are train data set missing values

<class 'pandas.core.frame.DataFrame'>
Int64Index: 1309 entries, 0 to 417
Data columns (total 12 columns):
 #   Column       Non-Null Count  Dtype  
---  ------       --------------  -----  
 0   PassengerId  1309 non-null   int64  
 1   Survived     891 non-null    float64
 2   Pclass       1309 non-null   int64  
 3   Name         1309 non-null   object 
 4   Sex          1309 non-null   object 
 5   Age          1046 non-null   float64
 6   SibSp        1309 non-null   int64  
 7   Parch        1309 non-null   int64  
 8   Ticket       1309 non-null   object 
 9   Fare         1308 non-null   float64
 10  Cabin        295 non-null    object 
 11  Embarked     1307 non-null   object 
dtypes: float64(3), int64(4), object(5)
memory usage: 132.9+ KB

# Exploratory data analysis

<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/1.PNG">
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/2.PNG">
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/3.PNG">
<img src = "https://github.com/Jyothif/Titanic_Disaster_Deployment/blob/main/images/4.PNG">

# Model Building

# Model Performance

# Deployment

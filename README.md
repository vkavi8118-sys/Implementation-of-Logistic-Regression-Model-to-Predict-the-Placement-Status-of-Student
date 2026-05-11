# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*

import pandas as pd
df=pd.read_csv("Placement_Data.csv")
df.head()
df1=df.copy()
df1.head()
df1=df1.drop(['sl_no','salary'],axis=1)
df1.isnull().sum()
df1.duplicated().sum()
df1

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()

df1["gender"]=le.fit_transform(df1["gender"])
df1["ssc_b"]=le.fit_transform(df1["ssc_b"])
df1["hsc_b"]=le.fit_transform(df1["hsc_b"])
df1["hsc_s"]=le.fit_transform(df1["hsc_s"])
df1["degree_t"]=le.fit_transform(df1["degree_t"])
df1["workex"]=le.fit_transform(df1["workex"])
df1["specialisation"]=le.fit_transform(df1["specialisation"])
df1["status"]=le.fit_transform(df1["status"])
df1

x=df1.iloc[:, : -1]
x
y=df1["status"]
y

from sklearn.model_selection import train_test_split

x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)
from sklearn.linear_model import LogisticRegression
model=LogisticRegression(solver="liblinear")
model.fit(x_train,y_train)
y_pred=model.predict(x_test)

from sklearn.metrics import accuracy_score,confusion_matrix,classification_report

accuracy=accuracy_score(y_test,y_pred)
confusion=confusion_matrix(y_test,y_pred)
cr=classification_report(y_test,y_pred)

print("Accuracy score:",accuracy)
print("\nConfusion matrix:\n",confusion)
print("\nClassification Report:\n",cr)

from sklearn import metrics

cm_display=metrics.ConfusionMatrixDisplay(confusion_matrix=confusion,display_labels=[True,False])
cm_display.plot()
Developed by: Kavinaya V
RegisterNumber:  212225230133
*/
```

## Output:
<img width="832" height="580" alt="WhatsApp Image 2026-05-11 at 4 07 25 PM" src="https://github.com/user-attachments/assets/9149bff7-4f98-4af9-abfd-c61c78df3458" />
<img width="588" height="344" alt="image" src="https://github.com/user-attachments/assets/58ffa0a1-45ef-42a9-8f75-a746773df2f7" />

## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.

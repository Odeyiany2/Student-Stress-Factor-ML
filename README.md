# Student-Stress-Factor-Machine Learning

This Machine Learning project is aimed at understanding what impacts stress of Engineering students the most. The dataset for this project was gotten from [Kaggle](https://www.kaggle.com/datasets/samyakb/student-stress-factors) 

### Overview
In this project, I used python libraries to gain a deeper insight on the dataset. I went further to use machine learning techniques to build a model capabale of categorizing the 
academic performance of students based on features such as level of stress, extracurricular activities and others. The model will be deployed using streamlit to enable an interactive web application that students can use. 

### Python Libraries
These are the libraries I used for this project: 
- Data Exploration & Preprocessing : `pandas` `numpy` 
- Data Visualization : `matplotlib` `seaborn`
- Machine Learning : `scikit-learn` `joblib`
- Deployment : `streamlit`

### Data Acquisition & Preprocessing Techniques
The following techniques were applied to preprocess the data:
- Renaming the columns
- Removing irrelevant columns and rows

### Data Visualization Insights
From the univariate, bivariate and multivariate analysis, the following patterns were found:
- An equal proportion of students have very high level of stress to a low stress level but high stress levels don't assure a great academic performance
- A greater proportion of students who almost rarely engage in extracurricular activities have more than an average academic performance. An average proportion of students who engage in extracurricular activities daily also have more than an avearge academic performance.
- Students with both light and heavy study loads respectively tend to perform well in their academics. Thw number of students with heavy study load who perform below average academically are quite a few. 


### Notebook Structure
This depicts the workflow followed in the notebook.

```bash
├── Data Collection
├── Data Preprocessing
│   ├── renaming columns
├── Data Exploration
├── Model Building
│   ├── model training
│   ├── model evaluation
│   ├── saving the model
```

### Conclusion
The project successfully achieved its objective of predict students' performance on a scale of 1-5. The representations are as follows: **5 - great**, **1 - bad** and **2-4 - average**. Further work will involve training our model with a larger dataset so that the model can learn enough variation. 

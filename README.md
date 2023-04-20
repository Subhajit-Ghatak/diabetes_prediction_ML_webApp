#Diabetes prediction app using ML

Dataset of diabetes is taken from kaggle- https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset

This dataset contains 'outcome' which is our target attribute. That attribute contains two values 0 and 1. So our machine learning will be based on binary classification.

Using Random Forest model I select the principal attributes.

Then I used four models to predict the outcome:
1. K Nearest Neighbour Algorithm.
2. Gaussian Naive Bayes Algorithm.
3. Decision Tree Algorithm.
4. Logistic Regression.

Among these four models Gaussian Naive Bayes contains the most accuracy. So, I saved the model using pickle in .sav format and using streamlit I build the UI. 

Finally I hosted the UI in streamlit's cloud services- https://subhajit-ghatak-diabetes-prediction-ml-webapp-prediction-p27639.streamlit.app/

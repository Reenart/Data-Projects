**#Project Title: Expense Prediction Based on Health Indicators and Demographics**

**Project Description: **
This project aims to predict level of expenses based on various health indicators and demographic factors. The model uses multiple machine learning techniques to explore and compare their effectiveness in predicting expenses.
The models included are:
- Support Vector Machine (SVM)
- Naive Bayes
- Neural Network
- Multiple Linear Regression (MLR)
- Decision Tree
The data is manipulated and pre-processed using pandas to ensure the models receive well-structured input.

**#Getting Started**
Follow the instructions below to set up and run this project.

**#Prerequisites:**
Before you begin, ensure that you have the following installed:
Python 3.x
pip (for installing Python packages) or 
Jupyter Notebook (to run the code in a notebook interface)

**#Installing**
1. Clone the repository using Git Bash.
   Code: git clone https://github.com/username/Comparing_Models.ipynb
2. Navigate to the project directory.
   Code: cd  "projectname"
3. Install required libraries:
   Code: pip install -r requirements.txt
   This will have the following libraries installed: Pandas, Scikit-learn, Seaborn, matplotlib, and numpy.

**#Running the Models:**
1. Data Preparation
To run the project, open the Jupyter Notebook and run each cell in sequence:
- Libraries: The first code cell contains the libraries to run the models. If you didn't install them using GIT BASH, you could highlight and run this cell on Jupyter Notebook to have these libraries installed.
- Loading dataset: The third cell loads and previews the dataset
- Key Statistics: The fifth cell shows the key statistics of the dataset.

2.**#Data Manipulation:**
- Clean and transform the dataset.
- Handle missing values.
- Encode categorical features and scale numerical ones.
- Train and Test the dataset
- Split the data into training and testing sets.
- Train the models and evaluate them on the test set
  
3. **#Breakdown of Test:**
These models are run to predict expense level:
- Support Vector Machine (SVM): Finds the best way to separate data into categories.
- Naive Bayes: A fast and simple model that works well when features are mostly independent.
- Neural Network: A powerful model that learns complex patterns in the data.
- Multiple Linear Regression (MLR): A model that predicts values using a straight-line relationship between features.
- Decision Tree: A model that splits data into smaller groups based on rules, making it easy to understand.
  
**#To evaluate how well each model performs, these metrics are used:**
- Accuracy: How often the model predicts correctly.
- Precision: How many of the predicted positive results are actually correct.
- Recall: How well the model finds all the actual positive results.
- F1 Score: A balance between precision and recall, especially useful when the data is 
  unbalanced.
These evaluations help identify which model performs best and is most reliable for predicting expense levels, and in this analysis, the **Support Vector Machine (SVM) achieved the highest prediction accuracy of 99%**, making it the best model for predicting medical expense_level(dependent variable) based on the independent variables. This prediction is near to a perfect score, and this is because these models were run on a small dataset.

4. **#Deployment**
- To deploy the project for use on your own data, simply update the input data file with your dataset.
- Ensure that the models and their parameters are tuned for optimal performance based on your dataset.
  
**#Author**
Maureen Chukwu.

**#License:**
This project is licensed under the DC License.

**#Acknowledgement: **
Thank you to Professor Rejoy James and Ziyad Mohamed for their exceptional teaching and guidance, which helped me understand and work with these machine learning models.

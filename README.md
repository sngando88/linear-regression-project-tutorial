<!-- hide -->
# Linear Regression Project Tutorial
<!-- endhide -->

- In this project we will build a linear regression model to predict the insurance prima for an individual based on different factors.
- Start with your exploratory data analysis and data transformation if needed.
- Build your baseline model, measure your results and optimize your model.
- Finally, create a pipeline for your final model and put it in you app.py file. 

## 🌱  How to start this project

You will not be forking this time, please take some time to read this instructions:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the recently created repostiroy on Gitpod by using the [Gitpod button extension](https://www.gitpod.io/docs/browser-extension/).
3. Once Gitpod VSCode has finished opening you start your project following the Instructions below.

## 🚛 How to deliver this project

Once you are finished creating your linear regression model, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

**Predicting the medical insurance cost of a person**

This dataset has 7 columns. We will use the 'charges' column as the target variable because we want to create a model that predicts the cost of the insurance based on different factors.

Columns

- age: age of primary beneficiary.

- sex: insurance contractor gender, female or male.

- bmi: Body mass index.

- children: number of children covered by health insurance / Number of dependents.

- smoker: smoking.

- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

- charges: Individual medical costs billed by health insurance.



**Step 1:**

The dataset can be found in this project folder as 'medical_insurance_cost.csv' file. You are welcome to load it directly from the link (https://raw.githubusercontent.com/4GeeksAcademy/linear-regression-project-tutorial/main/medical_insurance_cost.csv), or to download it and add it to your data/raw folder. In that case, don't forget to add the data folder to the .gitignore file.

>If you find yourself struggling with this project, you can check out the solution guide: https://github.com/4GeeksAcademy/linear-regression-project-tutorial/blob/main/solution_guide.ipynb

Time to work on it!

**Step 2:**

Use the explore.ipynb notebook to find patterns and valuable information about relationships between features or between feature and target.

>Hint: There are no null values

Don't forget to write your observations.


**Step 3:**

Now that you have a better knowledge of the data, in your exploratory notebook create a first linear regression model with your data, in order to predict the insurance prima.

Choose a metric to measure your results.

**Step 4:**

Hypertune your model to improve your results.

Use the app.py to create your final machine learning modeling pipeline. 

Save your final model in the 'models' folder.

In your README file write a brief summary.

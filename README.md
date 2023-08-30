# Housing Habitability Prediction!
In this project, based on the given features like Property Type, Property Area, Number of Doors, Furnishing, Frequency of Powercuts, Power Backup Water Supply, Traffic Density Score, Crime Rate, Dust and Noise, Air Quality Index, Neighborhood Review in the data set predicted the Habitability Score for the houses. 

<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/39cb359c-de2e-4c73-8436-058e6970f578"  height="350" width="800"/>
</div>


##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/030e1f21-e04f-4cbd-b301-3576c8c1acc3"  width="48" height="48"> Aim:
This project is focused on developing an accurate predictive model to estimate the Habitability Score of houses using a range of input features. By leveraging machine learning methodologies, the objective is to create a dependable model aiding prospective homebuyers and renters in making informed decisions regarding potential residences.

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/057551de-877a-4a41-916c-d47e81053404"  width="48" height="48"> Objectives:

- **Data Exploration:**
  - During the data extraction phase, key tasks encompassed assessing data shape, generating a statistical summary, and validating column quantity to establish a solid analytical groundwork."

- **Data Cleaning:**
  - Duplicate Detection and Removal:
      - To maintain dataset integrity, an exhaustive search was conducted to identify and eliminate duplicate records. This step ensured the dataset's accuracy by avoiding repetition of data       points.

  - Handling Null and Noisy Values:
    - Strategic techniques were employed to address null and noisy values. For missing values, imputation methods were applied to replace them with reasonable approximations. Noise reduction techniques were also                 implemented to enhance data reliability by filtering out irrelevant or inconsistent data points.

  - Elimination of Redundant Columns:
    - In the pursuit of a streamlined dataset, redundant columns—those offering minimal or negligible information—were systematically pinpointed. Once identified, these columns were eliminated, contributing to an                optimized dataset for subsequent analyses and model training.

  - Data Visualisation:
    - Utilized Visual Analytical Techniques and employed pair plots and heatmaps to assess interrelationships among numerical variables, box plots to identify potential outliers, and bar plots to evaluate the distribution       of categorical attributes.  can i write like this

  - Scaling and Encoding:
    - **Standardization** technique was applied to achieve uniform scales for numerical features, ensuring equal contribution of variables to the model.
    - **One-hot encoding** was employed to convert categorical attributes into numeric representations, facilitating seamless integration into the predictive model.
      
- **Data Preparation:**
    - In this phase, the dataset was structured and formatted to be ready for model training. This included splitting the data into training and testing sets, enabling the assessment of model performance on unseen data.

- **Model Building:**
    - Utilizing a Linear Regression model,  predicted the target variable, Habitability Score.  Then assessed the model's performance through metrics like Mean Square Error, R2 Score, and Accuracy for a thorough 
      evaluation.

<div id="header" align="center">
   <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/5536e887-9221-4ba2-89bc-5f01a55c3e92"  height="500" width="800"/>
   <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/116f408d-70cb-4171-aa3d-6a23e5233a8c"  height="500" width="800"/>
</div>
 

## Accuracy:
1. r2 Score =  0.5952475258109688
2. mean_squared_error =  80.5783149568078
3. mean_absolute_error =  7.225712659162546
4. root_mean_absolute_error =  8.976542483429117
 
After creating model (i.e., Linear Regression Model) got R2_Score as 0.59524 which is equal to 0.6, which means our model is neither bad nor the perfectly good model, but it is a good model.

## Python Libraries Used:
- **Pandas** simplifies data manipulation with versatile structures like DataFrames, essential for tasks from loading to preprocessing in data analysis.

- **Seaborn, Matplotlib** visualization libraries empower users to create insightful plots, enhancing data exploration.

- **Sklearn** provides a comprehensive toolkit for building and evaluating machine learning models.




("Linear regression is a simple but powerful machine learning algorithm that predicts a numeric value based on one or more input variables.")

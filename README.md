# **:Housing Habitability Prediction:**
In this project, based on the given features like Property Type, Property Area, Number of Doors, Furnishing, Frequency of Powercuts, Power Backup Water Supply, Traffic Density Score, Crime Rate, Dust and Noise, Air Quality Index, Neighborhood Review in the data set predicted the Habitability Score for the houses. 

<div id="header" align="center">
    <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/39cb359c-de2e-4c73-8436-058e6970f578"  height="350" width="800"/>
</div>

##  <img src="https://github.com/yasmeenustad/Placements-Data-Analysis-Excel-Project/assets/112754746/030e1f21-e04f-4cbd-b301-3576c8c1acc3"  width="48" height="48"> Aim:

This project is focused on developing an accurate predictive model to estimate the Habitability Score of houses using a range of input features. By leveraging machine learning methodologies, the objective is to create a dependable model aiding prospective homebuyers and renters in making informed decisions regarding potential residences.

##  <img src="https://github.com/yasmeenustad/ML-Housing-Habitability-Project/assets/112754746/f028cb01-2b46-4803-9876-9600d9d87b7b"  width="48" height="48"> Python Libraries Used:

- **Pandas** simplifies data manipulation with versatile structures like DataFrames, essential for tasks from loading to preprocessing in data analysis.

- **Seaborn, Matplotlib** visualization libraries empower users to create insightful plots, enhancing data exploration.

- **Sklearn** provides a comprehensive toolkit for building and evaluating machine learning models.
  
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
      
    - **Linear regression** is a simple but powerful machine learning algorithm that predicts a numeric value based on one or more input variables.

<div id="header" align="center">
   <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/1d9fdf25-b76c-4477-91af-fc0297aae7bf"  height="300" width="700"/>
   <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/116f408d-70cb-4171-aa3d-6a23e5233a8c"  height="300" width="700"/>
   <img src="https://github.com/yasmeenustad/Housing_Habitability-Prediction-ML-Project/assets/112754746/a8da6e18-6f51-45e9-9e05-235d1be21645"  height="300" width="700"/>
   <img src="https://github.com/yasmeenustad/Excel-Based-Placements-Data-Analysis/assets/112754746/1f2808c3-11ba-47df-a97f-e28c17e86239"  height="300" width="700"/>
</div>

## Evaluation metrics with Accuracy:
1. r2 Score =  0.5952475258109688
2. mean_squared_error =  80.5783149568078
3. mean_absolute_error =  7.225712659162546
4. root_mean_absolute_error =  8.976542483429117

<div id="header" align="center">
   <img src="https://github.com/yasmeenustad/ML-Housing-Habitability-Project/assets/112754746/0f47941f-4471-4b82-b2bd-a62fc4460dd9"  height="200" width="700"/>
</div>
 
An R-squared (R2) score of 0.59524 (approximately 0.6) indicates that our linear regression model explains about 60% of the variance in the dependent variable. It suggests a moderate level of predictive power, neither extremely strong nor weak, and its suitability depends on specific context and goals.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/603ad77e-2212-4b07-a75a-ffcabb0538f4" width="70" height="50"> Challenges:

- **Data Quality Assurance:**
    - Ensuring data integrity through processes like duplicate detection, null value handling, and column elimination poses a significant challenge. Guaranteeing that the dataset is clean and reliable is crucial for            accurate analysis and modeling.

- **Feature Engineering and Representation:**
    - Converting categorical attributes through one-hot encoding and achieving uniform scales for numerical features through standardization can be challenging. Effective feature engineering and representation are 
      critical for building accurate predictive models.

## <img src="https://github.com/yasmeenustad/Swiggy-data-Analysis/assets/112754746/2e256cec-1421-4c5f-9913-052a53dc470f" width="70" height="50"> Learnings:

- **Data Exploration:**
    - During this phase, critical tasks involve shaping the data, generating comprehensive statistical summaries, and rigorously validating column quantities to establish a robust foundation for analytical work.

- **Data Cleaning:**
    - Duplicate Detection and Removal:
      - To maintain data integrity, a meticulous search was conducted to identify and expunge duplicate records, ensuring data accuracy by eliminating redundant entries.
        
    - Handling Null and Noisy Values:
      - Strategic techniques were employed to address missing and noisy values, using imputation methods to replace missing data with reasonable approximations and noise reduction techniques to enhance data reliability by 
        filtering out irrelevant or inconsistent data points.
        
    - Elimination of Redundant Columns:
      - In pursuit of an optimized dataset, columns providing minimal or negligible information were systematically identified and subsequently removed, contributing to a streamlined dataset for subsequent analyses and 
        model training.

- **Scaling and Encoding:**
    - Standardization:
      - Standardization techniques were applied to achieve uniform scales for numerical features, ensuring equitable variable contributions to the predictive model.
        
    - One-Hot Encoding:
      - Categorical attributes were transformed into numeric representations through one-hot encoding, facilitating seamless integration into the predictive modeling process.
        
- **Data Preparation:**
      - This phase involved structuring and formatting the dataset for model training by partitioning it into training and testing sets, enabling the evaluation of model performance on previously unseen data.

- **Model Building:**
      - Employing a Linear Regression model, predictions were made for the target variable, Habitability Score, followed by a comprehensive assessment of model performance using metrics such as Mean Square Error, R2               Score, and Accuracy, ensuring a thorough model evaluation.

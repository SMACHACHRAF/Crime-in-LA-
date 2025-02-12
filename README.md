# Crime Prediction in Los Angeles using Machine Learning  

## Introduction  
This project is part of a semester project for the **Machine Learning** course. The goal is to predict crime categories in Los Angeles using a **Decision Tree Classifier**. The dataset contains information about different crimes committed in Los Angeles. The objective is to train a model that can accurately classify crimes based on the available features while carefully addressing issues of **overfitting** and **underfitting**.  

## Dataset  
The dataset used is based on public crime data from Los Angeles.  
- **Content:** It includes details such as the time, location, and category of the crime.  
- **Preprocessing:** The raw data was cleaned and transformed to enhance prediction accuracy.  

## Data Preprocessing  
The following preprocessing steps were applied:  
1. **Handling Missing Values:** Removing or replacing null values.  
2. **Encoding Categorical Variables:** Converting categorical data into numerical format using One-Hot Encoding.  
3. **Normalization and Standardization** of continuous variables to improve model performance.  
4. **Feature Engineering:** Creating new features based on logical combinations of existing data.  

## Machine Learning Model  
The chosen model for this project is the **Decision Tree Classifier** from `scikit-learn`.  
- **Why this model?**  
  - Easy to interpret.  
  - Suitable for complex datasets with non-linear relationships.  
  - Efficient for medium-sized datasets.  

### Model Building Steps  
1. **Data Splitting:** Dividing the dataset into training and testing sets (80% - 20%).  
2. **Model Training:** Fitting the model on the training data.  
3. **Avoiding Overfitting and Underfitting:**  
   - **Cross-validation** was used to ensure the model generalizes well to new data.  
   - **Hyperparameter tuning** was applied to optimize the tree depth and prevent overfitting.  
4. **Evaluation:** Using metrics such as accuracy, confusion matrix, and classification report.  

### Results  
The model was evaluated using key metrics:  
- **Accuracy:** ≈ 85%  
- **Confusion Matrix:** Visualizing classification errors.  
- **Error Analysis:** Suggestions for improvement, such as using more advanced models like Random Forest or Gradient Boosting.  

## Future Improvements  
- Test other algorithms like **Random Forest** or **Gradient Boosting**.  
- Add more data to enrich the feature set.  
- Perform advanced hyperparameter optimization to further improve performance.  

## Tools and Technologies  
- **Python**  
- **Jupyter Notebook**  
- **Pandas, NumPy** for data manipulation  
- **scikit-learn** for machine learning  
- **Matplotlib, Seaborn** for data visualization  

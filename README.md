# Life Expectancy Prediction Project - WHO Dataset

## Project Overview
This project focused on predicting life expectancy across 183 countries using data provided by the World Health Organisation (WHO). The dataset spans the years 2000 to 2015 and includes a variety of population statistics. The aim was to develop two continuous predictive models for life expectancy—one using minimal data inputs for privacy-conscious scenarios and another leveraging a more extensive feature set for greater accuracy.

### Objectives:
1. **Develop Predictive Models**: Create two linear regression models:
   - A minimalistic model requiring the least sensitive data.
   - An advanced model using a more comprehensive dataset.
2. **Incorporate Ethical Considerations**: Assess and select features based on their ethical implications.
3. **Build an Interactive Function**: Deploy the models into a Python function that:
   - Accepts relevant population data as input.
   - Prompts the user to consent to using advanced population data.
   - Provides life expectancy predictions based on the selected model.
4. **Evaluate Model Performance**: Compare the results against a baseline RMSE of 2, established by a competitor team.

## Notebooks Overview
The project involved several Python Jupyter Notebooks, each focusing on a different aspect of the pipeline:

### 1. **EDA and Feature Engineering.ipynb**
- Performed exploratory data analysis to understand the dataset.
- Identified missing values, data distributions, and correlations among features.
- Engineered new features to enhance the predictive power of the models.
- Documented insights on feature selection for both minimalistic and advanced models.

### 2. **Advanced Model.ipynb**
- Built the advanced linear regression model using extensive features.
- Optimised the model for accuracy by tuning parameters and handling multicollinearity.
- Achieved predictions with an RMSE below the baseline of 2.

### 3. **ethical_model.ipynb**
- Focused on constructing the minimalistic model with limited, non-sensitive features.
- Incorporated ethical considerations into feature selection to maintain data privacy.
- Ensured the model provided acceptable accuracy while protecting sensitive data.

### 4. **arif_function.ipynb**
- Combined the outputs of the minimalistic and advanced models into a single Python function.
- Implemented a user consent mechanism to select the appropriate model based on data availability.
- Designed the function for interactive use, making predictions based on user input.

### 5. **WHO Dataset - MetaData.ipynb**
- Analyzed the metadata of the dataset to document feature descriptions and their relevance.
- Used this analysis to guide feature selection and ensure alignment with ethical considerations.

## Tools and Libraries Used
- **Python**: Primary programming language.
- **Jupyter Notebooks**: Interactive environment for analysis and model development.
- **Libraries**:
  - `pandas` and `numpy`: Data manipulation and preprocessing.
  - `scikit-learn`: Model building and evaluation.
  - `matplotlib` and `seaborn`: Data visualization.

## Ethical Considerations
The project emphasised responsible data usage by:
- Limiting the use of sensitive features in the minimalistic model.
- Providing transparency about data requirements and their implications through the interactive function.
- Aligning with ethical data practices to address privacy concerns raised by countries.

## Conclusion
This project successfully developed two predictive models and an interactive function to estimate life expectancy while balancing accuracy and ethical considerations. The advanced model outperformed the baseline RMSE, and the minimalistic model offered a privacy-conscious alternative, showcasing the potential for scalable and ethical data-driven solutions in public health.

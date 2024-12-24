# Global_Health_ML

# Disease Prediction Model

This project involves building a machine learning model to predict disease curability based on various features such as the prevalence rate, treatment type, healthcare access, and more. The model is trained on a dataset containing historical disease data from multiple countries and uses various classification and regression algorithms to make predictions.

## Features

The dataset includes the following columns:
- **Country**: Country where the disease is prevalent.
- **Year**: Year of the data entry.
- **Disease Name**: The name or identifier of the disease.
- **Disease Category**: Classification of the disease (e.g., infectious, chronic).
- **Prevalence Rate (%)**: Percentage of the population affected by the disease.
- **Incidence Rate (%)**: Rate of new cases in the population.
- **Mortality Rate (%)**: Rate of deaths due to the disease.
- **Age Group**: Age groups affected by the disease.
- **Gender**: Gender affected by the disease.
- **Population Affected**: Number of people affected by the disease.
- **Healthcare Access (%)**: Percentage of the population with access to healthcare.
- **Doctors per 1000**: Number of doctors available per 1000 people.
- **Hospital Beds per 1000**: Number of hospital beds available per 1000 people.
- **Treatment Type**: Type of treatment available for the disease.
- **Average Treatment Cost (USD)**: Average cost of treatment.
- **Availability of Vaccines/Treatment**: Whether vaccines or treatments are available for the disease.
- **Recovery Rate (%)**: Percentage of people who recover from the disease.
- **DALYs**: Disability-adjusted life years for the disease.
- **Improvement in 5 Years (%)**: Projected improvement in disease outcomes over the next five years.
- **Per Capita Income (USD)**: Average income per person in the country.
- **Education Index**: Education level index for the country.
- **Urbanization Rate (%)**: Percentage of people living in urban areas.

## Machine Learning Models

The following machine learning models are used in this project:
- **Decision Tree Classifier**: Used for predicting the disease curability class.
- **HistGradientBoosting Classifier**: Another classification algorithm used for disease curability prediction.
- **LightGBM Classifier**: A more efficient and faster classification model for disease curability prediction.
- **Decision Tree Regressor**: Used for regression tasks like predicting prevalence rates.
- **HistradientBoostingRegressor**: Another regression algorithm used for regression tasks like predicting prevalence rates.

## Steps to Reproduce

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/disease-prediction-model.git
   cd disease-prediction-model

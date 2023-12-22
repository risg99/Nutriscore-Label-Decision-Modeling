# Nutriscore Label Decision Modeling

This repository represents the culmination of work completed as part of a Decision Modeling Course. The project is structured into various sections, each contributing to the development and analysis of the NutriScore label decision model.

## Objective
The primary goal of this project is to create and assess a NutriScore label decision model using data from OpenFoodFacts. The model involves data extraction, preprocessing, and the construction of various models to assign a NutriScore label to food products.

## Sections Overview

### Data Processing
1. **Data Extraction:** The project begins by extracting relevant data from OpenFoodFacts. The extracted data is preprocessed to ensure its suitability for further analysis. This process is carried out in the file [`code\extract_products_by_category.ipynb`](code/extract_products_by_category.ipynb), resulting in the creation of [`/data/final_preprocessed_data.csv`](data/final_preprocessed_data.csv).

### NutriScore Additive Model
2. **Model Development:** This section is dedicated to constructing the NutriScore additive model:
   - **Correlation Analysis:** Explore data correlations and initiate the additive model in [`code\correlations.ipynb`](code/correlations.ipynb). This notebook visualizes correlations within the data that are essential for modeling.
   - **Additive Model Creation:** Calculate nutrielement points in [`code\additive_model.ipynb`](code/additive_model.ipynb). The resulting data is saved in [`/data/final_preprocessed_data_points.csv`](data/final_preprocessed_data_points.csv).
   - **Grade Calculation:** Generate NutriScore grades based on the model and store results in [`/data/final_preprocessed_data_points_grades.csv`](data/final_preprocessed_data_points_grades.csv).
   - **Visualization:** Utilize various visualizations, such as bar charts and confusion matrices, to effectively represent and analyze the NutriScore model's outcomes.

### Electri-tri Model
3. **Electri-tri Model Construction:** This section details the creation of both optimistic and pessimistic Electri-tri models. The process, outlined in [`code\electri_model.ipynb`](code/electri_model.ipynb), involves building profiles and creating these specialized models.

### Machine Learning Models
4. **Machine Learning Model Building:** In addition to the NutriScore additive model and Electri-tri models, this section explores the development of machine learning-based models. These models, documented in [`code\machine_learning_model.ipynb`](code/machine_learning_model.ipynb), complement the decision-making process.

### Comparative Analysis
5. **Comparison with Other Models:** Finally, a comparative analysis is conducted by evaluating and contrasting the results obtained in this project with other students' models. The comparison is detailed in [`code\compare_model.ipynb`](code/compare_model.ipynb).

**Note:** Ensure all necessary libraries and their versions are installed as per the specifications listed in [`/requirements.txt`](requirements.txt).

## Usage
Refer to individual notebooks within the `code` directory for detailed implementation, methodologies, and results corresponding to each phase of the NutriScore label decision model.

Feel free to explore and contribute to the project, and don't hesitate to reach out for further inquiries or suggestions.

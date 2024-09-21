
# AI Customer Churn Prediction Project

## Overview

This project is designed to predict customer churn using various machine learning models. The goal is to identify customers who are likely to stop using the services of a company. The project includes data preprocessing, model training, evaluation, and deployment of the model through a web application and an executable file.

## Project Structure

- **`app.py`**: The main application script for deploying the churn prediction model as a web service.
- **`churn.csv`**: The dataset containing customer information and churn labels, consisting of approximately 7,000 entries with 21 features.
- **`requirements.txt`**: A list of Python libraries required to run the project.
- **`models/`**: Directory containing the saved machine learning models.
- **`Project_section1.ipynb`**: Jupyter Notebook for initial data exploration and preprocessing.
- **`Project_section11.ipynb`**: Jupyter Notebook for model training and evaluation.
- **`function_for_dataframe.ipynb`**: Contains custom functions used for data manipulation and analysis.
- **`model_load.py`**: Script for loading and using the trained models in the application.
- **`Amirhossein_Ashoori_99541065_AI_project.pdf`**: Detailed documentation and report of the project.
- **Various Images**: Visual representations of model structures, feature importances, and decision trees.

## Steps to Reproduce

### 1. Set Up the Environment
   - Clone the repository to your local machine.
   - Install the required Python packages using `pip`:

     ```bash
     pip install -r requirements.txt
     ```

### 2. Data Exploration and Preprocessing
   - The dataset consists of around 7,000 entries with 21 features. 
   - Open `Project_section1.ipynb` to explore the dataset and perform initial data cleaning.
   - This step includes:
     - Handling missing values.
     - Encoding categorical variables.
     - Removing irrelevant features based on the project's requirements.
     - Scaling the features to prepare them for model training.

### 3. Model Training and Evaluation
   - Use `Project_section11.ipynb` to train various machine learning models, including Decision Trees, Random Forests, and Neural Networks.
   - For each method, corresponding charts are generated to illustrate model accuracy and feature importance.
   - Detailed analysis and performance metrics are provided for each model.
   - The best-performing model is selected and saved in the `models/` directory.

### 4. Deployment
   - The `app.py` script is used to deploy the trained model as a web service.
   - Additionally, an executable file (exe) is provided, allowing users to interact with the model without needing a Python environment.
   - Users can run the executable to upload their data and view the prediction results.

### 5. Analysis and Visualization
   - Various images (`.png` files) in the repository illustrate the structure of the neural network, decision trees, and feature importances.
   - These visualizations provide insights into the model's decision-making process.

### 6. Documentation
   - The `Amirhossein_Ashoori_99541065_AI_project.pdf` contains a detailed report of the entire project, including methodologies, results, and conclusions.

## Conclusion

This project demonstrates a complete machine learning pipeline, from data preprocessing to model deployment, for predicting customer churn. It provides practical examples of how machine learning can be applied to real-world business problems. The provided executable file makes it easy for users to upload their data and immediately see results, making the project highly accessible and user-friendly.


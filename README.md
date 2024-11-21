# Classification Model with SVM
This project demonstrates the development and evaluation of a robust classification model using Support Vector Machines (SVM). The notebook focuses on handling class imbalance, feature scaling, and model evaluation to ensure high performance and generalizability.

## Project Objectives
The primary objectives of this project are:

- To preprocess and clean the dataset effectively.
- To address class imbalance using synthetic oversampling techniques (SMOTE).
- To build and train a Logistic regression and SVM classification model for predicting the target variable.
- To evaluate model performance using metrics like classification report and select the best model.
- To analyze feature importance for understanding model predictions.
- To save the trained model for deployment purposes.

## Workflow
1. Data Preparation
- Loaded and cleaned the dataset.
- Handled class imbalance using SMOTE.
- Scaled features using StandardScaler to ensure compatibility with SVM.
2. Model Training
- Split the dataset into training and testing sets.
- Trained an Logistic Regression on the scaled training data.
- Trained an SVM classifier on the scaled training data.
- Evaluated performance metrics to ensure balanced and accurate predictions.
3. Model Evaluation
- First I used Logictic Regression Model which achieved 86% score. 
- Then I used SVC which achieved high accuracy (92%) on the test dataset.
- The SVM model showed balanced precision-recall scores across all classes, indicating good generalizability.
4. Feature Importance
- Used techniques like permutation importance to identify the most impactful features driving predictions.
5. Model Saving
- Saved the trained model as a serialized file (.pkl) for easy deployment.

## Requirements
To run this project, ensure the following dependencies are installed:


pip install sklearn 
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install imblearn
pip install pickle  

## Usage
*Clone the repository:*


git clone <https://github.com/kunzula/Loan_prediction_model.git >
cd Loan_prediction_model  

Run the Jupyter Notebook:


Import pickle


Pass new data to the predict function for real-time predictions.

## Results
The SVM model outperformed LogisticRegression, achieving an accuracy of 92% and balanced F1-scores for both classes.

Feature importance analysis highlighted the key drivers influencing predictions, aiding interpretability and further decision-making.
## Next Steps
Deploy the saved model into a production environment.

Enhance the model further with advanced optimization techniques or ensemble methods.

Explore domain-specific insights derived from the feature importance analysis.

## Author
Developed by OLAKUNLE ADEOTI OPELOYERU, a passionate DATA SCIENTIST with a focus on creating scalable, impactful solutions.

For queries or collaborations, feel free to reach out at <adeoti179@gmail.com
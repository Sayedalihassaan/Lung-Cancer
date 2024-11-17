# Lung Cancer Prediction

This project focuses on predicting the likelihood of an individual being diagnosed with lung cancer based on various lifestyle and health-related features. The model leverages machine learning techniques to predict whether a person has lung cancer based on factors like age, smoking habits, fatigue, shortness of breath, and more.

## Dataset Overview

The dataset consists of **310 records** and **16 features**, including both **categorical** and **numerical** data. The target variable is `LUNG_CANCER`, indicating whether the individual has been diagnosed with lung cancer (YES or NO).

### Features:

1. **GENDER**: Gender of the individual (M: Male, F: Female).
2. **AGE**: Age of the individual (56 to 74 years).
3. **SMOKING**: Whether the individual smokes (1: No, 2: Yes).
4. **YELLOW_FINGERS**: Whether the individual has yellow fingers (1: No, 2: Yes).
5. **ANXIETY**: Whether the individual experiences anxiety (1: No, 2: Yes).
6. **PEER_PRESSURE**: Whether the individual experiences peer pressure (1: No, 2: Yes).
7. **CHRONIC DISEASE**: Whether the individual has a chronic disease (1: No, 2: Yes).
8. **FATIGUE**: Whether the individual experiences fatigue (1: No, 2: Yes).
9. **ALLERGY**: Whether the individual has allergies (1: No, 2: Yes).
10. **WHEEZING**: Whether the individual experiences wheezing (1: No, 2: Yes).
11. **ALCOHOL CONSUMING**: Whether the individual consumes alcohol (1: No, 2: Yes).
12. **COUGHING**: Whether the individual experiences coughing (1: No, 2: Yes).
13. **SHORTNESS OF BREATH**: Whether the individual experiences shortness of breath (1: No, 2: Yes).
14. **SWALLOWING DIFFICULTY**: Whether the individual has difficulty swallowing (1: No, 2: Yes).
15. **CHEST PAIN**: Whether the individual experiences chest pain (1: No, 2: Yes).
16. **LUNG_CANCER**: Target variable indicating if the individual has lung cancer (YES or NO).

## Project Goals

The main goal of this project is to build a predictive model that can help in early detection of lung cancer. The features chosen in the dataset include lifestyle, symptoms, and health conditions, all of which are significant in determining the likelihood of lung cancer.

## Tools and Technologies Used

- **Python**: Programming language used for data analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Scikit-learn**: Machine learning library for model building and evaluation.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: For interactive development and testing.
  
## Installation and Setup

To run this project locally, you'll need to have Python installed on your system. You can set up the environment with the following steps:

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/lung-cancer-prediction.git
    ```

2. Navigate into the project directory:

    ```bash
    cd lung-cancer-prediction
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the project:

    - Open the `lung_cancer_prediction.ipynb` file in Jupyter Notebook or any other IDE.
    - Execute the cells to start training the model.

## Features and Functionality

- **Data Preprocessing**: Cleaning and preparing the dataset for training, including handling missing values, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: Analyzing the distribution of features and their relationships with the target variable (`LUNG_CANCER`).
- **Model Building**: Implementing and training multiple machine learning algorithms (e.g., Logistic Regression, Decision Trees, Random Forest, etc.) to predict lung cancer.
- **Evaluation**: Using performance metrics like accuracy, precision, recall, and F1-score to evaluate the model.
- **Prediction**: Once the model is trained, it can be used to predict whether a person is likely to have lung cancer based on the provided features.

## Results and Accuracy

The model's performance is evaluated using various metrics, and the most accurate model is selected for predictions. The final model can achieve a high accuracy score in predicting lung cancer.

## Contribution

Contributions are always welcome! If you would like to improve the project or add new features, feel free to fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thank you to the contributors of this dataset and to the open-source community for the tools and libraries used to develop this project.
  
---

Feel free to replace any specific parts (e.g., the GitHub link and dependencies) to match your actual setup. This README will help make your project clear, professional, and accessible to a broad audience!

# Student Performance Analysis Project 📚🎓

This end-to-end machine learning project aims to understand how students' performance in tests is influenced by various factors such as gender, ethnicity, parental level of education, lunch, and test preparation course. The project includes the development of a machine learning model, continuous integration and deployment (CI/CD) pipelines, and MLOps practices for deploying the model on cloud platforms like AWS, Azure, and GCP.

## Table of Contents 📋

- [Student Performance Analysis Project 📚🎓](#student-performance-analysis-project-)
  - [Table of Contents 📋](#table-of-contents-)
  - [Problem Statement 🎯](#problem-statement-)
    - [Variables](#variables)
  - [Project Structure 📁](#project-structure-)
  - [Setup and Installation ⚙️](#setup-and-installation-️)
  - [Data Collection 📊](#data-collection-)
  - [Data Preprocessing 🧹](#data-preprocessing-)
  - [Exploratory Data Analysis (EDA) 📊📈](#exploratory-data-analysis-eda-)
  - [Machine Learning Model 🤖](#machine-learning-model-)
  - [CI/CD Pipeline 🔄](#cicd-pipeline-)
  - [MLOps 🛠️](#mlops-️)
  - [Deployment on Cloud ☁️](#deployment-on-cloud-️)
  - [Usage 🚀](#usage-)
  - [Contributing 🤝](#contributing-)
  - [License 📜](#license-)

## Problem Statement 🎯

The project addresses the question of how various factors, such as gender, ethnicity, parental level of education, lunch, and test preparation course completion, influence students' test scores in math, reading, and writing.

### Variables

- **Gender:** Sex of students (Male/Female)
- **Race/Ethnicity:** Ethnicity of students (Group A, B, C, D, E)
- **Parental Level of Education:** Parents' final education (Bachelor's Degree, Some College, Master's Degree, Associate's Degree, High School)
- **Lunch:** Whether students had standard lunch or free/reduced lunch
- **Test Preparation Course:** Completion status of the test preparation course (Complete/Not Complete)
- **Math Score**
- **Reading Score**
- **Writing Score**

## Project Structure 📁

- **`src/`**: Contains source code for data preprocessing, model development, and deployment.
- **`notebooks/`**: Jupyter notebooks for exploratory data analysis and model development.
- **`data/`**: Dataset used for training and testing the model.
- **`tests/`**: Unit tests for the project.
- **`configs/`**: Configuration files for CI/CD and MLOps pipelines.
- **`docs/`**: Documentation files for the project.

## Setup and Installation ⚙️

- Ensure you have Python 3.7+ installed.
- Install dependencies using `pip install -r requirements.txt`.

## Data Collection 📊

- The dataset used for this project can be found in the `data/` directory.
- The data was collected from [https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977](KAGGLE), and details about its structure are provided in the data directory.

## Data Preprocessing 🧹

- The `src/data_preprocessing.py` script handles data cleaning, handling missing values, and encoding categorical variables.

## Exploratory Data Analysis (EDA) 📊📈

- Explore the `notebooks/EDA.ipynb` notebook for a detailed analysis of the dataset.

## Machine Learning Model 🤖

- The `src/model.py` script contains the code for training and saving the machine learning model.

## CI/CD Pipeline 🔄

- The CI/CD pipeline is configured using [CI/CD tool], and the configuration file can be found in `configs/ci_cd.yml`.

## MLOps 🛠️

- The MLOps pipeline is implemented using [MLOps tool], and the configuration file is located in `configs/mlops.yml`.

## Deployment on Cloud ☁️

- The model can be deployed on AWS, Azure, or GCP using the deployment scripts in the `src/deployment/` directory.

## Usage 🚀

- Follow the instructions in the `docs/usage.md` file for guidance on how to use the project.

## Contributing 🤝

- Contributions are welcome! Check the `CONTRIBUTING.md` file for guidelines.

## License 📜

- This project is licensed under the [MIT License](LICENSE).

Feel free to reach out for any questions or clarifications. Happy coding! 🚀

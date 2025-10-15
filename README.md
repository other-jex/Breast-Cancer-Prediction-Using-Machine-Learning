Breast Cancer Prediction Using Machine Learning
📘 Project Overview

This project utilizes machine learning algorithms to predict the diagnosis of breast cancer, classifying tumors as either benign or malignant. By analyzing features derived from cell nuclei, the model assists in early detection, aiding healthcare professionals in making informed decisions.

🧪 Dataset

The model is trained on the Breast Cancer Wisconsin (Diagnostic) Dataset, which includes the following features:

Radius

Texture

Perimeter

Area

Smoothness

Compactness

Concavity

Concave Points

Symmetry

Fractal Dimension

These features are computed for each cell nucleus present in the breast cancer biopsies.

⚙️ Technologies Used

Python 3.x

Jupyter Notebook

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

🚀 Getting Started
Prerequisites

Ensure you have Python 3.x installed. It is recommended to use a virtual environment.

Installation

Clone the repository:

git clone https://github.com/other-jex/Breast-Cancer-Prediction-Using-Machine-Learning.git


Navigate into the project directory:

cd Breast-Cancer-Prediction-Using-Machine-Learning


Install the required dependencies:

pip install -r requirements.txt

🧠 Model Training

The project includes a Jupyter Notebook (breast_cancer_prediction.ipynb) where the following steps are performed:

Data Preprocessing: Loading and cleaning the dataset.

Exploratory Data Analysis (EDA): Visualizing data distributions and relationships.

Feature Selection: Identifying the most relevant features for prediction.

Model Training: Training various machine learning models, including:

Support Vector Machine (SVM)

Logistic Regression

Random Forest

Model Evaluation: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

The notebook provides a step-by-step guide to understanding and implementing the model.

📈 Results

The models are evaluated based on their accuracy and other relevant metrics. Detailed performance comparisons are available in the notebook.

📁 Project Structure

The repository contains the following files and directories:

Breast-Cancer-Prediction-Using-Machine-Learning/
│
├── breast_cancer_prediction.ipynb       # Jupyter Notebook with model implementation
├── breast_cancer_wisconsin_data.zip     # Dataset file
├── requirements.txt                    # Python dependencies
└── README.md                           # Project documentation

📝 License

This project is licensed under the MIT License - see the LICENSE
 file for details.

📢 Acknowledgments

The dataset used in this project is from the UCI Machine Learning Repository.

Special thanks to the contributors and maintainers of the libraries and tools used in this project.

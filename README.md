# FraudBuster: A predictive model for detecting fraudulent automobile insurance claims

Fraudbuster is a machine learning-based system designed to detect fraudulent insurance claims. By analyzing historical data and identifying patterns, Fraudbuster predicts whether a car insurance claim is fraudulent or not. Using a variety of classification models (Logistic Regression, Random Forest, and XGBoost), along with feature selection techniques and hyperparameter tuning, the system is optimized for high accuracy and minimal false positives. It leverages the power of scikit-learn for model building and evaluation, making it an efficient tool for fraud detection in the insurance industry.

Follow the instructions below to set up the environment and run the project locally.

---

## Project Setup

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/Moosa013/Workplace-Project
```
___

### 2. Set Up a Virtual Environment
We recommend using a virtual environment to manage project dependencies. Here’s how to set it up:

#### 2.1 Create the Environment
Create a new virtual environment using conda. You only need to do this step once.

``` bash
# create the conda environment
conda create --name <env_name> python=3.8
```

#### 2.2 Activate the new evironment 
Activate your newly created virtual environment:

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
```

___
### 3. Install Dependencies
Now that you have the virtual environment set up, install the required dependencies listed in the requirements.txt file:

```bash
# install the requirements for this project
pip install -r requirements.txt
```

For running the project scripts or Jupyter notebooks, simply execute the desired script or open the notebook and run the cells.

___ 

### Project Requirements
The following Python packages are used in this project for various tasks, such as data manipulation, machine learning, and visualization:

#### Core Libraries
* **pandas**: For data manipulation and analysis, especially with tabular data.
* **numpy**: For numerical computing and working with arrays and matrices.
* **scikit-learn**: For machine learning tasks such as classification, regression, and model evaluation.
* **xgboost**: For efficient and scalable gradient boosting models.

#### Visualization Libraries
* **matplotlib**: For creating static, animated, and interactive plots and visualizations.
* **seaborn**: For statistical data visualization built on top of Matplotlib.

#### Model Libraries
* **LogisticRegression**: A linear model for binary classification tasks.
* **RandomForestClassifier**: An ensemble learning method for classification based on decision trees.
* **XGBClassifier**: A gradient boosting algorithm for classification tasks, known for high performance.

#### Feature Engineering and Selection
* **StandardScaler**: For standardizing features by removing the mean and scaling to unit variance.
* **OneHotEncoder**: For converting categorical variables into binary (0 or 1) vectors.
* **SelectKBest**: For selecting the top 'K' features based on a chosen statistical test.
* **RFE**: For recursive feature elimination, selecting the most important features.
* **PCA**: For dimensionality reduction, retaining maximum variance in the data.
* **LabelEncoder**: For converting categorical labels into numerical form.

#### Model Validation
* **cross_val_score**: For evaluating a model’s performance using cross-validation.
* **train_test_split**: For splitting data into training and testing subsets.

#### Evaluation Metrics
* **accuracy_score**, **precision_score**, **recall_score**, **f1_score**: For evaluating model performance across different classification metrics.
* **roc_auc_score**: For assessing the model’s ability to discriminate between classes.
* **confusion_matrix**: For understanding the classification performance and errors.
* **classification_report**: For generating a detailed classification report including precision, recall, and F1-score.

#### Utility
* **warnings**: For suppressing unnecessary warnings to maintain a clean output.
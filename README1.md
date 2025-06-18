# Cervical Cancer Prediction Project Adaptation

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Anne-Okingo/Decision-Tree-Algorithm.git

cd Decision-Tree-Algorithm
```
### 2.  Create Virtual Environment
```bash
python3 -m venv myenv
source myenv/bin/activate  
```
### 3. Install Dependencies
```bash
pip install pandas numpy matplotlib scikit-learn pydotplus six
pip install notebook ipykernel
```
### 4. Launch Jupyter Notebook
```bash
jupyter notebook --no-browser
```
Copy the access token from the console

Paste it at http://localhost:8888 in your browser

### 5 Dataset Preparation
Place your cervical cancer dataset in the project root as:
 for example data/cervical_cancer.csv

Update the dataset path in the notebook:

python
### Replace:
```bash
 data = pd.read_csv('data/breast_cancer.csv')
 ```
 With:
 ```bash
data = pd.read_csv('data/cervical_cancer.csv')  # Relative path
```
Development Workflow
Making Changes
Run cells sequentially in the notebook

Modify as needed:

Update column names for cervical cancer features

Adjust target variable (e.g., Biopsy instead of diagnosis)

commit and push
# Toxic Comment Classification – Mini Project

This repository contains a Jupyter Notebook for classifying toxic comments using a machine learning pipeline. The notebook includes steps for preprocessing, training, and evaluating models using the dataset from the **Kaggle Toxic Comment Classification Challenge**.

## 📁 Files
- `Mini_project.ipynb` – Main notebook for data analysis and model training
- `README.md` – Instructions to set up and run the project

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/toxic-comment-classification.git
cd toxic-comment-classification
2. Set Up a Python Environment
We recommend using a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
If requirements.txt is not provided, install these manually:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn nltk tqdm kaggle
📥 Downloading the Dataset from Kaggle
This project uses the dataset from Toxic Comment Classification Challenge.

Steps:
Log in to Kaggle.

Go to your account page and scroll down to API section.

Click on "Create New API Token". This downloads a file called kaggle.json.

Move kaggle.json to the root of your project or to a secure directory.

Use the Kaggle API to Download the Dataset
bash
Copy
Edit
mkdir ~/.kaggle
mv /path/to/kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json

kaggle competitions download -c jigsaw-toxic-comment-classification-challenge
unzip jigsaw-toxic-comment-classification-challenge.zip -d data/
This will give you:

train.csv

test.csv

sample_submission.csv

📊 Running the Notebook
Once the dataset is downloaded and placed in a data/ folder, open and run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Mini_project.ipynb
Follow the steps in the notebook to train and evaluate your models.

📌 Notes
Make sure train.csv and test.csv are placed in the correct path as expected by the notebook (usually ./data/).

The notebook supports customization and extension, such as trying different models, hyperparameter tuning, etc.

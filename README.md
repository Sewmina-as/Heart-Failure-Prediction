# 🫀 Heart Failure Prediction

Cardiovascular diseases are the leading cause of death globally, claiming an estimated 17.9 million lives each year. This project utilizes clinical data and supervised machine learning to predict the likelihood of a fatal heart failure event, aiming to support early detection and timely medical intervention.

## 📊 Dataset

- **Source**: [Kaggle — Heart Failure Prediction Dataset](https://www.kaggle.com/code/karnikakapoor/heart-failure-prediction-ann/input)
- **Target Variable**: `DEATH_EVENT` (Binary Classification: `1` = Deceased, `0` = Survived)
- **Clinical Features**: 
  `age`, `anaemia`, `creatinine_phosphokinase`, `diabetes`, `ejection_fraction`, `high_blood_pressure`, `platelets`, `serum_creatinine`, `serum_sodium`, `sex`, `smoking`, `time`

## 🛠️ Tech Stack

- **Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: scikit-learn (Logistic Regression)

## 📈 Results

The predictive model is built using **Logistic Regression** and evaluated using a confusion matrix and classification report. 
- **Model Accuracy**: **84%** on the test dataset.

## 🚀 How to Run Locally

1. **Clone the repository**:
 
2.Set up a virtual environment (Recommended to avoid dependency conflicts):

On Windows:
   Bash
   python -m venv venv
   venv\Scripts\activate

On macOS/Linux:
   Bash
   python3 -m venv venv
   source venv/bin/activate

3.Install the required dependencies:
   Bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter

4.Add the dataset:
Download the dataset from the Kaggle link.
Extract the .csv file and place it in the same directory as the notebook (or inside a designated data/ folder if you are using one).

5.Launch Jupyter Notebook:
   Bash
   jupyter notebook heart_failure.ipynb
   This will open the notebook in your web browser where you can execute the cells sequentially.

👤 Author

Achintha Sewmina Gamage
Computer Science Undergraduate @ University of Kelaniya, Sri Lanka
Email: achinthasewmina22@gmail.com
LinkedIn: Achintha Sewmina Gamage
(www.linkedin.com/in/achintha-sewmina-gamage-699665331)
GitHub: @sewmina-as


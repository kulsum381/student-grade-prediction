# student-grade-prediction 
# 📊 Student Performance Prediction using Logistic Regression - week 2 AI and ML project

This is a simple Machine Learning project that predicts whether a student will **pass (1)** or **fail (0)** based on two key factors:
- 📘 **Study Hours**
- 🏫 **Attendance**

The model uses **Logistic Regression** for binary classification and is implemented in **Python** using **Google Colab**.

---

## 📁 Dataset

The dataset used is a **manually created synthetic dataset** (in the code), which includes the following columns:
- `StudyHours`: Number of hours the student studies
- `Attendance`: Attendance percentage (%)
- `Result`: 0 = Fail, 1 = Pass

Here's a sample of the dataset:

| StudyHours | Attendance | Result |
|------------|------------|--------|
| 2          | 65         | 0      |
| 5          | 80         | 1      |
| 7          | 95         | 1      |

You can extend this dataset by adding more realistic or collected data.

---

## 🧰 Tools and Libraries Used

This project was implemented in **Google Colab** using the following Python libraries:

| Library | Purpose |
|--------|---------|
| `pandas` | Data handling and manipulation |
| `matplotlib.pyplot` | Data visualization |
| `scikit-learn (sklearn)` | Machine learning model and evaluation metrics |

**scikit-learn submodules used**:
- `train_test_split`: To split data into training and testing sets
- `LogisticRegression`: To build and train the model
- `accuracy_score`, `confusion_matrix`, `classification_report`: To evaluate the model

---

## 📌 How the Project Works

### 1. **Data Preparation**
- The dataset is created manually using Python dictionaries and converted into a `pandas` DataFrame.
- Features (`StudyHours`, `Attendance`) are selected as input variables.
- `Result` is selected as the target output.

### 2. **Data Visualization**
- A **scatter plot** is created using `matplotlib.pyplot` to visualize the relationship between study hours, attendance, and student result.

### 3. **Model Training**
- The data is split into **training** (80%) and **testing** (20%) sets using `train_test_split`.
- A **Logistic Regression model** is trained using the training data.

### 4. **Model Prediction**
- The model makes predictions on the test set.
- You can also make predictions for **new data** by entering custom values.

### 5. **Model Evaluation**
- **Accuracy**: Shows the percentage of correct predictions.
- **Confusion Matrix**: Displays actual vs. predicted outcomes.
- **Classification Report**: Shows precision, recall, and F1-score.

---

## ✅ Example Output


# placement_prediction_and_analysis_system
**Placement Prediction and Analysis System**

This system is designed to predict the placement status of students based on various factors such as academic performance, internship status, aptitude scores, knowledge of data structures and algorithms, and project involvement. The dataset used in this project was created manually using Excel and then imported into a SQLite database using SQL. New candidate data provided by the user is inserted into the database for prediction. The system utilizes machine learning models including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors for prediction, with their respective accuracies reported for evaluation.

---

### Sections:

1. **Introduction**
   - A predictive tool for assessing students' placement prospects based on a custom dataset and machine learning models.

2. **Technologies Used**
   - Python, SQLite, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn

3. **Data Acquisition**
   - Creation of dataset using Excel and storage in SQLite database.
   - Data was exported to a SQLite database using SQL commands.

4. **Exploratory Data Analysis (EDA)**
   - Visualization of dataset characteristics such as college tier distribution, average 12th marks by tier, subjects distribution, etc.

5. **Data Preprocessing**
   - Conversion of categorical variables to numerical format for model training.

6. **Model Training**
   - Utilization of machine learning models including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors.
     Evaluation of model performance with accuracy scores for each model.

7. **Prediction**
   - Interactive prediction interface for evaluating a new candidate's placement status based on user-provided information.

8. **Dataset Export**
   - Exporting the updated dataset to a CSV file after inserting new candidate data.

9. **Comparative Analysis**
   - Visualization depicting the comparative analysis of different models based on their test accuracies.

---

### Installation:

1. **Clone the repository:**
   ```
   git clone <repository_URL>
   ```

2. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   - Execute the main Python script.

---

4.**Model Training and Performance:**
----------------------------------
Model performance for Test set: Logisitic Regression
- Accuracy: 98.0000
- Fl score: 98.3897
- Precision: 99.1429
- Recall: 98.0000
===================================


----------------------------------
Model performance for Test set: Decision Tree
- Accuracy: 100.0000
- Fl score: 100.0000
- Precision: 100.0000
- Recall: 100.0000
===================================


----------------------------------
Model performance for Test set: Random Forest
- Accuracy: 100.0000
- Fl score: 100.0000
- Precision: 100.0000
- Recall: 100.0000
===================================


----------------------------------
Model performance for Test set: Support Vector Machine
- Accuracy: 99.0000
- Fl score: 98.7525
- Precision: 99.0101
- Recall: 99.0000
===================================


----------------------------------
Model performance for Test set: K-Nearest Neighbors
- Accuracy: 99.5000
- Fl score: 99.4506
- Precision: 99.5025
- Recall: 99.5000
===================================

- These accuracy scores demonstrate the performance of each model in predicting the placement status of students.
- Among these models, K-Nearest Neighbors (KNN)--99.5% and Support Vector Machine (SVM) accuracy is 99%, followed by Logistic Regression exhibited slightly lower accuracy at 98%.
- Decision Tree and Random Forest achieved the highest accuracy of 100%.

------

### Usage:

1. **Data Acquisition:**
   - The dataset was created manually using Excel and then imported into the SQLite database using SQL.

2. **Exploratory Data Analysis (EDA):**
   - Visualize dataset characteristics using provided functions.

3. **Model Training:**
   - Train multiple machine learning models on the dataset.

4. **Prediction:**
   - Input candidate details through the interactive interface to predict placement status.

---

### Contributors:
- **Vishal V V**

### Acknowledgments:
- Libraries and resources utilized for this project are credited accordingly within the code.

### License:
- This project is licensed under the [MIT License](link) - see the [LICENSE.md](link) file for details.

# placement_prediction_and_analysis_system
**Placement Prediction and Analysis System**

This system is designed to predict and analyze the placement status of students, leveraging various academic and extracurricular factors. Through a combination of exploratory data analysis (EDA) and machine learning techniques, it provides insights into the factors influencing placement outcomes and offers predictive capabilities for assessing a candidate's likelihood of placement.

---

### Sections:

1. **Introduction**
   - Welcome to the Placement Prediction and Analysis System, developed by Vishal V V. This system aims to facilitate informed decision-making in the recruitment process by predicting the placement status of students based on their academic records, internships, aptitude scores, and more.

2. **Technologies Used**
   - Python, SQLite, Pandas, NumPy, Matplotlib, Seaborn, Plotly, scikit-learn.

3. **Data Acquisition**
   - Reads data from a CSV file and stores it in a SQLite database for efficient data handling.

4. **Exploratory Data Analysis (EDA)**
   - Visualizes dataset characteristics such as college tier distribution, average 12th marks by tier, subject distribution, etc., to gain insights into the dataset.

5. **Data Preprocessing**
   - Converts categorical variables to numerical format for model training.

6. **Model Training**
   - Trains multiple machine learning models including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors to predict placement outcomes.

7. **Prediction**
   - Provides an interactive interface for predicting a candidate's placement status based on user-provided information.

8. **Dataset Export**
   - Exports the updated dataset to a CSV file after inserting new candidate data.

9. **Comparative Analysis**
   - Compares the performance of different machine learning models based on their test accuracies.

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

### Usage:

1. **Data Acquisition:**
   - Store the dataset file in the specified directory.
   - Execute the script to read and store data in the SQLite database.

2. **Exploratory Data Analysis (EDA):**
   - Visualize dataset characteristics using provided functions.

3. **Model Training:**
   - Train multiple machine learning models on the dataset.

4. **Prediction:**
   - Input candidate details through the interactive interface to predict placement status.

---

### Contributors:
- Vishal V V

### Acknowledgments:
- Special thanks to the OpenAI team for providing the ChatGPT model, which assisted in generating this README.

### License:
- This project is licensed under the MIT License - see the [LICENSE.md](link) file for details.

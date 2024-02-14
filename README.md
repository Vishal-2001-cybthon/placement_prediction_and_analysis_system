# placement_prediction_and_analysis_system
**Placement Prediction and Analysis System**

This system is designed to predict the placement status of students based on various factors such as academic performance, internship status, aptitude scores, knowledge of data structures and algorithms, and project involvement. The dataset used in this project was created manually using Excel and then imported into a SQLite database using SQL. New candidate data provided by the user is inserted into the database for prediction. The system utilizes machine learning models including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors for prediction, with their respective accuracies reported for evaluation.

---

### Sections:

1. **Introduction**
   - Brief overview of the Placement Prediction and Analysis System.

2. **Technologies Used**
   - List of technologies and libraries used in the project.

3. **Data Acquisition**
   - Creation of dataset using Excel and storage in SQLite database.

4. **Exploratory Data Analysis (EDA)**
   - Visualization of dataset characteristics such as college tier distribution, average 12th marks by tier, subjects distribution, etc.

5. **Data Preprocessing**
   - Conversion of categorical variables to numerical format for model training.

6. **Model Training**
   - Training various machine learning models and evaluating their performance metrics on the test set.

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

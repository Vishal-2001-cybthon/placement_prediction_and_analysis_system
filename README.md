# placement_prediction_and_analysis_system
**Placement Prediction and Analysis System**

This system, developed by Vishal V V, offers a comprehensive solution for predicting and analyzing placement outcomes for students. Leveraging a self-created dataset and utilizing SQL for data export, it empowers users to explore, understand, and predict placement probabilities based on a variety of factors. Furthermore, it facilitates the addition of new candidate data through user input, ensuring real-time evaluation and insights.

---

### Technologies Used:

- Python
- SQLite
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

### Data Acquisition:

The system employs a self-created dataset, meticulously curated to capture various attributes influencing placement outcomes. The data is imported into a SQLite database using Python's Pandas library, enabling seamless storage and retrieval for analysis and modeling.

### Exploratory Data Analysis (EDA):

Through visualizations generated using Matplotlib, Seaborn, and Plotly, the system offers a detailed EDA of the dataset. Users can explore trends, distributions, and correlations among different features, gaining valuable insights into factors affecting placement success.

### Data Preprocessing:

Before model training, the dataset undergoes preprocessing steps such as categorical variable conversion and scaling. This ensures optimal performance of machine learning algorithms in predicting placement outcomes.

### Model Training:

The system trains multiple machine learning models, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and K-Nearest Neighbors. Each model's performance metrics are evaluated to determine its efficacy in predicting placement probabilities.

### Prediction:

Users can input candidate details through an interactive interface, enabling the system to predict placement status based on the provided information. The addition of new candidate data enriches the dataset and enhances prediction accuracy.

### Dataset Export:

Utilizing SQL, the system exports the updated dataset to a CSV file after incorporating new candidate data. This ensures data integrity and enables further analysis or model retraining.

---

### Usage:

1. **Clone the repository:**
   ```
   git clone <repository_URL>
   ```

2. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   - Execute the main Python script to explore, analyze, and predict placement outcomes.

4. **Contribute:**
   - Feel free to contribute to the dataset or codebase to enhance system functionality and accuracy.

---

### Contributor:

**Vishal V V**

### License:

- This project is licensed under the MIT License - see the [LICENSE.md](link) file for details.

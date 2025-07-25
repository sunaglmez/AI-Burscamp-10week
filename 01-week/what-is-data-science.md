# What is Data Science?

### 📖 Definition:

**Data Science** is the process of extracting meaningful insights from structured or unstructured data. It combines statistics, programming, domain expertise, and problem-solving skills.

In short:

> "The science of generating value from data."

## Main Goals of Data Science:

1. **Descriptive Analysis:**  
   Answers the question: *"What happened?"*  
   Example: Sales increased by 10% this quarter.

2. **Diagnostic Analysis:**  
   Investigates: *"Why did it happen?"*  
   Example: Why did sales drop?

3. **Predictive Analysis:**  
   Predicts: *"What will happen?"*  
   Example: 1000 units are expected to be sold next month.

4. **Prescriptive Analysis:**  
   Advises: *"What should we do?"*  
   Example: Which campaign would increase sales?

## 🛠️ What Tools Does Data Science Use?

| Field                      | Tools and Methods                        |
|---------------------------|------------------------------------------|
| **Programming**           | Python, R, SQL                           |
| **Data Processing**       | Pandas, NumPy                            |
| **Visualization**         | Matplotlib, Seaborn, Plotly              |
| **Statistics & Probability** | Mean, variance, hypothesis testing   |
| **Machine Learning**      | scikit-learn, XGBoost, LightGBM          |
| **Big Data**              | Spark, Hadoop                            |
| **Databases & Querying**  | SQL, PostgreSQL, MongoDB                 |
| **Reporting**             | Power BI, Tableau, Streamlit             |

# 👨‍🔬 What Does a Data Scientist Do?

### General Role:

A data scientist is someone who works with data, analyzes it, builds models, and interprets the results in a way that creates **business value**.

## Typical Data Science Workflow (Pipeline):

1. **Problem Definition:**

   * What is the business problem? (e.g., Why are customers leaving?)
   * How can data science help solve it?

2. **Data Acquisition:**

   * Sources: databases, APIs, files, surveys, etc.
   * Methods: SQL, web scraping, sensor data, etc.

3. **Data Cleaning:**

   * Filling missing values
   * Detecting outliers
   * Data type conversions

4. **Exploratory Data Analysis (EDA):**

   * Understanding the data
   * Visualizations
   * Group-based analysis

5. **Feature Engineering:**

   * Creating new variables
   * Encoding categorical variables
   * Scaling numerical values

6. **Modeling (Machine Learning):**

   * Regression, classification, clustering
   * Model selection, training, and evaluation

7. **Model Evaluation:**

   * Accuracy, Precision, Recall, F1-score, ROC-AUC
   * Cross-validation

8. **Model Deployment:**

   * Creating APIs, dashboards, or pipelines
   * Tools: Streamlit, FastAPI, Flask

9. **Reporting and Business Impact:**

   * Data storytelling
   * Presenting to decision-makers
   * Contributing to strategy

## Real-World Example Projects

| Problem               | What a Data Scientist Does                  |
|----------------------|---------------------------------------------|
| Customer churn        | Builds a churn prediction model             |
| Fraud detection       | Develops a fraud detection system           |
| Sales forecasting     | Performs time series analysis               |
| Marketing targeting   | Creates segmentation and recommendation systems |

## Data Science vs. Other Roles

| Role                | Main Focus                                      |
|---------------------|-------------------------------------------------|
| **Data Analyst**     | Analyzes existing data and generates reports    |
| **Data Scientist**   | Data analysis + modeling + prediction           |
| **ML Engineer**      | Puts machine learning models into production    |
| **Data Engineer**    | Collects, stores, and prepares data for use     |

* "Data science is not just about coding, it's about understanding problems and offering solutions."  
* "We can't build good models without understanding the data. Start with the basics!"  
* "A data scientist combines math, coding, and business intelligence."

---

# 🔢 Types of Variables in Data Science

Correctly identifying variable types is essential for accurate data analysis. In pandas, data types such as `object`, `int`, and `float` shown via `.dtypes` are not always sufficient. Instead, variables should be classified based on their **meaning**.

## 🔹 Categorical Variables

Variables that represent categories or classes — even if they appear numeric.

**Examples:** `Sex`, `Embarked`, `Pclass`, `Survived`

## 🔹 Numerical Variables

Variables that represent actual quantities and support mathematical operations.

**Examples:** `Age`, `Fare`

## 🔹 Numeric but Categorical (num_but_cat)

These variables have a data type of `int` or `float`, but they **function as categories**.

- Typically contain fewer than 10 unique values.

**Examples:** `Pclass`, `Survived`

## 🔹 High Cardinality Categorical Variables

Categorical variables with **many unique values** (e.g., more than 20).

- Usually of type `object`.
- Often contain text or identifiers (e.g., names, codes).
- Can cause issues in encoding and modeling.
- May be excluded from basic analysis or handled separately.

**Examples:** `Name`, `Ticket`, `Cabin`

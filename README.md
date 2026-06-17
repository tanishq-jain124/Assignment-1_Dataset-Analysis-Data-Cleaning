# Assignment-1_Dataset-Analysis-Data-Cleaning

# 🚢 Titanic Dataset Analysis Project

## 📌 Project Overview
This project performs complete data analysis on the famous Titanic dataset downloaded from Kaggle. The analysis includes data cleaning, handling missing values, removing duplicates, statistical analysis, generating insights, and creating visualizations using Python.

The project is beginner-friendly and demonstrates the basic workflow of data analysis and visualization.

---

# 📂 Dataset
Dataset Used: Titanic Dataset  
Source: Kaggle Titanic Dataset

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

---

# 📊 Features Implemented

## ✅ Data Cleaning
- Checked dataset information
- Removed unnecessary columns
- Handled missing values
- Removed duplicate rows

## ✅ Null Value Handling
- Filled missing Age values using mean
- Filled missing Embarked values using mode
- Removed Cabin column due to excessive null values

## ✅ Statistical Analysis
- Average age calculation
- Maximum fare analysis
- Minimum fare analysis
- Passenger count analysis

## ✅ Insights Generated
- Survival statistics
- Gender distribution
- Passenger class distribution
- Fare trends

---

# 📈 Visualizations Included

### 📌 Bar Chart
Shows survival count comparison.

### 📌 Pie Chart
Displays gender distribution percentage.

### 📌 Line Graph
Represents fare trend of passengers.

---

# 🖼️ Sample Output

## Survival Count Bar Chart

```python
plt.bar(['Not Survived', 'Survived'], survival_count)
```

## Gender Distribution Pie Chart

```python
plt.pie(gender_count, labels=gender_count.index, autopct='%1.1f%%')
```

## Fare Trend Line Graph

```python
plt.plot(df['Fare'].head(50))
```

---

# ▶️ How to Run the Project

## Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib
```

## Step 2: Download Dataset

Download the Titanic dataset from Kaggle and place it in the project folder.

## Step 3: Run the Python File

```bash
python project.py
```

---

# 📁 Project Structure

```bash
Titanic-Data-Analysis/
│
├── Titanic-Dataset.csv
├── project.py
├── README.md
└── screenshots/
```

---

# 📌 Key Insights

- Most passengers traveled in 3rd class.
- Male passengers were higher in number.
- Survival rate was lower than the death rate.
- Passenger fare distribution varied significantly.

---

# 🎯 Learning Outcomes

Through this project, you can learn:

- Data preprocessing
- Data cleaning techniques
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib
- Statistical analysis using Pandas

---

# 📚 References

- Kaggle Titanic Dataset
- Pandas Documentation
- Matplotlib Documentation
- NumPy Documentation

---

# 👨‍💻 Author

Created for Data Analysis and Visualization Practice using Python.


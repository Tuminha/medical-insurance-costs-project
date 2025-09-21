# 🏥 U.S. Medical Insurance Costs Analysis Project

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Data Science](https://img.shields.io/badge/Data-Science-green?style=for-the-badge&logo=databricks&logoColor=white)
![CSV](https://img.shields.io/badge/Data-CSV-lightgrey?style=for-the-badge&logo=csv&logoColor=black)

</div>

## 📋 Project Overview

This project investigates a medical insurance costs dataset using Python data analysis techniques. The goal is to perform independent analysis on real-world data, building functions and class methods to explore patterns and relationships within the dataset.

### 🎯 Project Objectives

- [x] Work locally on your own computer
- [x] Import a dataset into your program
- [ ] Analyze a dataset by building out functions or class methods
- [ ] Use libraries to assist in your analysis
- [ ] Document and organize your findings
- [ ] Make predictions about a dataset's features based on your findings

---

## 📊 Dataset Information

The `insurance.csv` file contains the following columns:
- **age**: Age of the primary beneficiary
- **sex**: Insurance contractor gender (male/female)
- **bmi**: Body mass index
- **children**: Number of children covered by health insurance
- **smoker**: Smoking status (yes/no)
- **region**: The beneficiary's residential area in the US (northeast, southeast, southwest, northwest)
- **charges**: Individual medical costs billed by health insurance

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries (pandas, numpy, matplotlib, seaborn)

### Installation

```bash
# Clone the repository
git clone https://github.com/Tuminha/medical-insurance-costs-project.git
cd medical-insurance-costs-project

# Install required packages
pip install pandas numpy matplotlib seaborn jupyter
```

---

## 📝 Project Tasks

### ✅ To Do
- [ ] **📋 Look over your dataset** - Open insurance.csv and examine the file structure
- [ ] **🎯 Scoping Your Project** - Plan your analysis scope and define goals
- [ ] **📥 Import your dataset** - Import insurance.csv into your Python file
- [ ] **💾 Save your dataset via Python variables** - Store dataset features in variables
- [ ] **🔧 Build out analysis functions or class methods** - Create analysis functions
- [ ] **🚀 Project Extensions** - Expand your analysis with additional features

### 🔄 In Progress
- *No tasks currently in progress*

### ✅ Done
- [x] **📄 Create comprehensive README** - Set up project documentation with task tracking

---

## 📋 Task Details

### 📋 Task 1: Look over your dataset
**Description:** Open insurance.csv and examine the file structure. Note how information is organized and consider what aspects you want to investigate.

**Key Questions:**
- How is the data organized?
- What patterns do you notice?
- What relationships might exist between variables?

**Steps:**
1. Open the `insurance.csv` file in a text editor or spreadsheet application
2. Examine the column headers and data types
3. Look for patterns in the data
4. Note any interesting observations

---

### 🎯 Task 2: Scoping Your Project
**Description:** Plan your analysis scope. Define goals, gather data, and consider analytical steps.

**Considerations:**
- What do you want to find out?
- Which analyses will be easier to perform?
- What are your project goals?

**Steps:**
1. Define your research questions
2. Identify key variables to analyze
3. Plan your analytical approach
4. Set realistic scope boundaries

---

### 📥 Task 3: Import your dataset
**Description:** Import insurance.csv into your Python file and inspect the contents.

**Steps:**
1. Use pandas to read the CSV file
2. Display basic information about the dataset
3. Check for missing values
4. Examine data types and structure

**Code Example:**
```python
import pandas as pd

# Import the dataset
insurance_data = pd.read_csv('insurance.csv')

# Display basic information
print(insurance_data.info())
print(insurance_data.head())
```

---

### 💾 Task 4: Save your dataset via Python variables
**Description:** Store dataset features in variables for analysis.

**Considerations:**
- What types of variables to use?
- How many variables to create?
- How will organization impact analysis?

**Steps:**
1. Extract columns into separate variables
2. Consider data types (lists, arrays, etc.)
3. Organize variables logically
4. Plan for easy access during analysis

---

### 🔧 Task 5: Build out analysis functions or class methods
**Description:** Create functions or class methods to perform your investigations.

**Approaches:**
- Statistical analysis functions
- Data visualization methods
- Correlation analysis
- Grouping and aggregation

**Example Functions:**
```python
def calculate_average_charges_by_smoker(data):
    """Calculate average insurance charges by smoking status"""
    return data.groupby('smoker')['charges'].mean()

def analyze_age_groups(data):
    """Analyze insurance charges by age groups"""
    # Implementation here
    pass
```

---

### 🚀 Task 6: Project Extensions
**Description:** Expand your analysis with additional features.

**Potential Extensions:**
- Organize findings into dictionaries or lists
- Make predictions about influential features
- Explore potential data bias
- Create visualizations and reports
- Build a simple prediction model

---

## 🛠️ Debugging Tips

<div style="background-color: #f8d7da; padding: 15px; border-radius: 5px; margin: 20px 0; border-left: 4px solid #dc3545;">

### Feeling stuck? Try these approaches:

1. **🔍 Google your question** - Check StackOverflow and Dev.to for solutions
2. **📚 Read the documentation** - Carefully review library documentation
3. **🦆 Rubber ducking** - Explain the problem to someone else
4. **👥 Get help** - Ask for another pair of eyes on your code

</div>

---

## 📚 Helpful Resources

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin: 20px 0;">

<a href="https://docs.python.org/3/" target="_blank" style="background-color: #007bff; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px; display: inline-block;">
  🐍 Python3 Documentation
</a>

<a href="https://docs.python.org/3/library/csv.html" target="_blank" style="background-color: #28a745; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px; display: inline-block;">
  📄 CSV Library
</a>

<a href="https://pandas.pydata.org/docs/" target="_blank" style="background-color: #17a2b8; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px; display: inline-block;">
  🐼 Pandas Documentation
</a>

<a href="https://matplotlib.org/stable/contents.html" target="_blank" style="background-color: #ffc107; color: black; padding: 10px 15px; text-decoration: none; border-radius: 5px; display: inline-block;">
  📊 Matplotlib Documentation
</a>

</div>

---

## 📈 Project Progress

<div style="background-color: #e9ecef; padding: 20px; border-radius: 10px; margin: 20px 0;">

**Overall Progress: 0 / 6 tasks completed (0%)**

<div style="background-color: #dee2e6; border-radius: 10px; height: 20px; margin: 10px 0;">
  <div style="background-color: #28a745; height: 100%; border-radius: 10px; width: 0%; transition: width 0.3s ease;"></div>
</div>

</div>

---

## 👨‍💻 Author

<div style="background-color: #f8f9fa; padding: 20px; border-radius: 10px; margin: 20px 0; text-align: center;">

**Francisco Barbosa**

<div style="margin: 15px 0;">

<a href="mailto:cisco@periospot.com" style="background-color: #6c757d; color: white; padding: 8px 12px; text-decoration: none; border-radius: 5px; margin: 5px; display: inline-block;">
  📧 Email
</a>

<a href="https://twitter.com/cisco_research" target="_blank" style="background-color: #1da1f2; color: white; padding: 8px 12px; text-decoration: none; border-radius: 5px; margin: 5px; display: inline-block;">
  🐦 Twitter/X
</a>

</div>

</div>

---

## 📄 License

This project is part of the CodeAcademy Data Science curriculum and is for educational purposes.

---

## 📝 How to Use This README

### Task Tracking
- Use the checkboxes `- [ ]` to mark tasks as complete by changing them to `- [x]`
- Move tasks between "To Do", "In Progress", and "Done" sections as you work
- Update the progress bar percentage manually as you complete tasks

### Progress Updates
To update your progress:
1. Check off completed tasks by changing `- [ ]` to `- [x]`
2. Move tasks between sections as needed
3. Update the progress percentage in the "Project Progress" section
4. Commit and push your changes to track your progress on GitHub

### Example Progress Update
```markdown
### ✅ Done
- [x] **📄 Create comprehensive README** - Set up project documentation with task tracking
- [x] **📋 Look over your dataset** - Open insurance.csv and examine the file structure
- [x] **🎯 Scoping Your Project** - Plan your analysis scope and define goals
```

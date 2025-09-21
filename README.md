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

<div style="background-color: #f8f9fa; padding: 20px; border-radius: 10px; margin: 20px 0;">

### ✅ To Do
<button onclick="toggleTask('task1')" style="background-color: #ffc107; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; margin: 5px;">📋 Look over your dataset</button>
<button onclick="toggleTask('task2')" style="background-color: #ffc107; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; margin: 5px;">🎯 Scoping Your Project</button>
<button onclick="toggleTask('task3')" style="background-color: #ffc107; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; margin: 5px;">📥 Import your dataset</button>
<button onclick="toggleTask('task4')" style="background-color: #ffc107; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; margin: 5px;">💾 Save your dataset via Python variables</button>
<button onclick="toggleTask('task5')" style="background-color: #ffc107; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; margin: 5px;">🔧 Build out analysis functions or class methods</button>
<button onclick="toggleTask('task6')" style="background-color: #ffc107; color: black; border: none; padding: 8px 16px; border-radius: 5px; cursor: pointer; margin: 5px;">🚀 Project Extensions</button>

### 🔄 In Progress
<div id="inProgress" style="min-height: 40px; background-color: #e3f2fd; border: 2px dashed #2196f3; border-radius: 5px; padding: 10px; margin: 10px 0;">
  <em>No tasks currently in progress</em>
</div>

### ✅ Done
<div id="done" style="min-height: 40px; background-color: #e8f5e8; border: 2px solid #4caf50; border-radius: 5px; padding: 10px; margin: 10px 0;">
  <em>No tasks completed yet</em>
</div>

</div>

---

## 📋 Task Details

<div id="task1" style="display: none; background-color: #fff3cd; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 4px solid #ffc107;">
  <h4>📋 Look over your dataset</h4>
  <p><strong>Description:</strong> Open insurance.csv and examine the file structure. Note how information is organized and consider what aspects you want to investigate.</p>
  <p><strong>Key Questions:</strong></p>
  <ul>
    <li>How is the data organized?</li>
    <li>What patterns do you notice?</li>
    <li>What relationships might exist between variables?</li>
  </ul>
</div>

<div id="task2" style="display: none; background-color: #fff3cd; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 4px solid #ffc107;">
  <h4>🎯 Scoping Your Project</h4>
  <p><strong>Description:</strong> Plan your analysis scope. Define goals, gather data, and consider analytical steps.</p>
  <p><strong>Considerations:</strong></p>
  <ul>
    <li>What do you want to find out?</li>
    <li>Which analyses will be easier to perform?</li>
    <li>What are your project goals?</li>
  </ul>
</div>

<div id="task3" style="display: none; background-color: #fff3cd; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 4px solid #ffc107;">
  <h4>📥 Import your dataset</h4>
  <p><strong>Description:</strong> Import insurance.csv into your Python file and inspect the contents.</p>
  <p><strong>Steps:</strong></p>
  <ul>
    <li>Use pandas to read the CSV file</li>
    <li>Display basic information about the dataset</li>
    <li>Check for missing values</li>
  </ul>
</div>

<div id="task4" style="display: none; background-color: #fff3cd; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 4px solid #ffc107;">
  <h4>💾 Save your dataset via Python variables</h4>
  <p><strong>Description:</strong> Store dataset features in variables for analysis.</p>
  <p><strong>Considerations:</strong></p>
  <ul>
    <li>What types of variables to use?</li>
    <li>How many variables to create?</li>
    <li>How will organization impact analysis?</li>
  </ul>
</div>

<div id="task5" style="display: none; background-color: #fff3cd; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 4px solid #ffc107;">
  <h4>🔧 Build out analysis functions or class methods</h4>
  <p><strong>Description:</strong> Create functions or class methods to perform your investigations.</p>
  <p><strong>Approaches:</strong></p>
  <ul>
    <li>Statistical analysis functions</li>
    <li>Data visualization methods</li>
    <li>Correlation analysis</li>
    <li>Grouping and aggregation</li>
  </ul>
</div>

<div id="task6" style="display: none; background-color: #fff3cd; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 4px solid #ffc107;">
  <h4>🚀 Project Extensions</h4>
  <p><strong>Description:</strong> Expand your analysis with additional features.</p>
  <p><strong>Potential Extensions:</strong></p>
  <ul>
    <li>Organize findings into dictionaries or lists</li>
    <li>Make predictions about influential features</li>
    <li>Explore potential data bias</li>
    <li>Create visualizations and reports</li>
  </ul>
</div>

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

<script>
function toggleTask(taskId) {
  const task = document.getElementById(taskId);
  const inProgress = document.getElementById('inProgress');
  const done = document.getElementById('done');
  
  if (task.style.display === 'none' || task.style.display === '') {
    task.style.display = 'block';
  } else {
    task.style.display = 'none';
  }
}

// Add drag and drop functionality for task management
function allowDrop(ev) {
  ev.preventDefault();
}

function drag(ev) {
  ev.dataTransfer.setData("text", ev.target.id);
}

function drop(ev) {
  ev.preventDefault();
  var data = ev.dataTransfer.getData("text");
  ev.target.appendChild(document.getElementById(data));
}
</script>

<style>
button:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  transition: all 0.3s ease;
}

a:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  transition: all 0.3s ease;
}

#inProgress, #done {
  transition: all 0.3s ease;
}

.task-item {
  background-color: white;
  padding: 10px;
  margin: 5px 0;
  border-radius: 5px;
  border: 1px solid #dee2e6;
  cursor: move;
}

.task-item:hover {
  background-color: #f8f9fa;
}
</style>

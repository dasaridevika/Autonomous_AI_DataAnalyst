# Autonomous_AI_DataAnalyst
# 🚀 InsightCore: Autonomous AI Data Analyst

> An AI-powered autonomous data analyst that performs data cleaning, analysis, visualization, and business insight generation using natural language commands.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red?style=for-the-badge&logo=streamlit)
![Gemini](https://img.shields.io/badge/Google-Gemini_AI-green?style=for-the-badge&logo=google)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-black?style=for-the-badge&logo=pandas)

---

## 📌 Project Overview

**InsightCore** is an autonomous AI Data Analyst capable of understanding natural language instructions and automatically performing data analysis tasks.

Users simply upload a CSV file and interact with the system in plain English.

The AI agent can:

- ✅ Clean datasets
- ✅ Remove missing values
- ✅ Detect outliers
- ✅ Generate visualizations
- ✅ Perform statistical analysis
- ✅ Create business insights
- ✅ Maintain dataset memory across interactions
- ✅ Execute AI-generated Python code autonomously

---

## ✨ Features

### 🤖 Autonomous AI Agent

- Powered by **Google Gemini 2.5 Flash**
- Understands natural language requests
- Generates executable Python code automatically

### 📊 Intelligent Data Analysis

- Exploratory Data Analysis (EDA)
- Descriptive statistics
- Correlation analysis
- Distribution analysis

### 🧹 Automated Data Cleaning

- Missing value handling
- Duplicate removal
- Outlier detection
- Feature engineering

### 📈 Dynamic Visualization

Supports automatic generation of:

- Histograms
- Boxplots
- Scatterplots
- Heatmaps
- Correlation matrices
- Distribution plots

### 💾 Persistent Workspace

- Dataset changes are automatically saved
- Maintains analysis history during the session

### 🖥️ Interactive Dashboard

Built with **Streamlit** featuring:

- KPI cards
- Dataset preview
- Analysis history
- Downloadable outputs
- Modern user interface

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| Programming Language | Python |
| Frontend | Streamlit |
| AI Model | Google Gemini 2.5 Flash |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```bash
InsightCore/
│
├── 01_First_AI_Agent.ipynb
├── 02_AI_Data_Analyst.ipynb
├── 03_Advanced_Ai_Data_Analyst.ipynb
├── 04_Automatic_AI_Analyst.ipynb
│
├── app.py
├── agent_working_dataset.csv
├── cleaned_dataset.csv
├── employees.csv
├── cleaned_employees.csv
│
├── AI_Analysis_Report.txt
│
├── annual_income_ev_adoption_likelihood_distribution.png
├── annual_income_vs_ev_adoption_likelihood.png
├── dept_outliers.png
├── psychological_correlations.png
│
├── requirements.txt
└── README.md
```

---

## 🧠 Architecture

```text
User Query
     │
     ▼
Gemini AI Agent
     │
     ▼
Python Code Generation
     │
     ▼
Sandbox Execution Engine
     │
     ▼
Dataset Analysis & Modification
     │
     ▼
Charts + Insights + Reports
```

---

## 📸 Sample Visualizations

### EV Adoption vs Annual Income

- High-income users are more likely to adopt EVs.
- High adoption groups exhibit greater income variability.

### Revenue Distribution by Department

- Revenue is evenly distributed across departments.
- No major anomalies were detected.

### Correlation Analysis

Important findings:

- Discounted Price and Actual Price show a strong positive correlation (**0.96**).
- Discount percentage has a weak negative relationship with price.
- Product ratings have little dependence on pricing variables.

---

## 🚀 Getting Started

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/InsightCore.git

cd InsightCore
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Gemini API Key

Set your API key as an environment variable:

```bash
export GEMINI_API_KEY="YOUR_API_KEY"
```

For Windows:

```bash
set GEMINI_API_KEY=YOUR_API_KEY
```

### 5. Run the Application

```bash
streamlit run app.py
```

---

## 💡 Example Queries

```text
Remove all missing values.

Generate a boxplot for annual income.

Find outliers in salary.

Create a correlation heatmap.

Provide business insights from this dataset.

Compare revenue across departments.

Visualize EV adoption likelihood.
```

---

## 🔮 Future Enhancements

- Multi-agent architecture
- SQL database integration
- PDF report generation
- Voice-enabled analytics
- Cloud deployment
- LangChain integration
- Predictive analytics capabilities

---

## 👨‍💻 Author

### Devika Dasari

**Data Analyst | AI Enthusiast | Data Engineer | Aspiring Data Scientist**

Passionate about building AI-driven solutions that automate business intelligence and decision-making.

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.

---

**Happy Coding! 🚀**

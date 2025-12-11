# AI-Assistant-Usage-Insights
An interactive **Power BI dashboard** that provides a deep understanding of how users engage with an AI assistant across different devices, categories, and model types.  
This project includes full **EDA**, **data cleaning**, and a multi-page analytics dashboard designed for business-ready insights.

---

## Project Overview

The goal of this project is to analyze AI assistant usage data and uncover:

- User behavior trends  
- Device usage distribution  
- Category-level engagement  
- Satisfaction patterns  
- Model preference across tasks  

This dashboard helps stakeholders quickly understand how users interact with the platform and where improvements can be made.

---

## Dashboard Preview

### 🔹 **Model Usage Trend Across Devices**
Tracks how frequently each AI model (GPT-4o, GPT-5, Mini, etc.) is used across desktop, mobile, tablet, and smart speakers.

### 🔹 **Usage Category Contribution**
A pie chart showing which categories—Productivity, Writing, Research, Entertainment, Coding, etc.—contribute most to overall usage.

### 🔹 **User Satisfaction Over Time**
Compares assistant model usage with monthly user satisfaction ratings.

### 🔹 **Device Usage Distribution**
A donut chart showing which device types users prefer.

### 🔹 **Average Session Duration**
Displays how long users typically engage with tasks like Coding, Productivity, Education, Writing, etc.

### 🔹 **Model Preference Trends**
Line charts comparing models across multiple categories.

All dashboard pages are interactive, filter-enabled, and designed with clean and consistent visuals.

---

## Exploratory Data Analysis (EDA)

The notebook `eda_datacleaning.ipynb` includes:

- Missing value handling  
- Outlier treatment  
- Data type corrections  
- Visual EDA  
- Category-level distributions  
- Feature engineering  
- Creation of `cleaned_data.csv` for the dashboard  

This ensures a reliable, well-structured dataset for Power BI.

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python (Pandas, Matplotlib)** | Data cleaning + EDA |
| **Jupyter Notebook** | Analysis workflow |
| **Power BI Desktop** | Dashboard creation |
| **CSV Data** | Processed dataset |

---

## Key Insights

- Desktop & Smart Speakers are the most preferred devices.  
- Coding and Productivity drive the longest session durations.  
- GPT-4o and GPT-5 perform consistently across most categories.  
- Satisfaction drops in March → potential UX or system concerns.  
- Productivity, Education, and Writing top the usage categories.

---

## How to Use This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/AI-Assistant-Usage-Dashboard.git

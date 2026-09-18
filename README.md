# Titanic Dataset - Exploratory Data Analysis (EDA)

This project focuses on analyzing the historic Titanic passenger dataset to uncover the key factors that influenced passenger survival rates. The main objective is to answer the question: **What kinds of passengers were more likely to survive?**

This repository contains data cleaning, insights generation, and visualizations built using Python's data science ecosystem.

## Project Objectives
* **Data Inspection:** Explore the structural shape, data types, and identify missing values within the dataset.
* **Feature Analysis:** Group and isolate survival frequencies relative to gender, socio-economic class (Pclass), and passenger age.
* **Data Visualization:** Build clear graphical distributions (bar charts, overlapping histograms) using Matplotlib and Seaborn.
* **Proportional Analysis:** Leverage relative frequencies to evaluate demographic distributions fairly without being misled by absolute passenger counts.

## Technologies Used
* **Python**
* **Pandas** (Data manipulation and cleaning)
* **Matplotlib** / **Seaborn** (Statistical data visualization)
* **Jupyter Notebook** (Interactive code execution and reporting)

## Key Analysis & Visualizations Included

### 1. Survival Rate by Gender
* **Method:** Categorical count analysis.
* **Insight:** Explored the dramatic variance in survival distributions between male and female passengers, validating the historic "women and children first" protocol.

### 2. Survival Breakdown by Passenger Class (Pclass)
* **Method:** Grouped and stacked bar charts.
* **Insight:** Assessed the raw volume and proportions of survival across 1st, 2nd, and 3rd-class tickets to determine how socio-economic standing impacted rescue prioritization.

### 3. Age Distribution vs. Survival
* **Method:** Overlapping continuous distribution histogram (5-year age bins).
* **Insight:** Isolated age groups to find distinct trends, such as high survival priority among toddlers and young children compared to the higher mortality rates observed among young adults.

## Getting Started

### Prerequisites
Ensure you have Python installed along with the required libraries. You can install the dependencies via pip:
```bash
pip install pandas matplotlib seaborn jupyter
```

### Running the Project
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Download the `train.csv` file from the [Kaggle Titanic Competition](https://kaggle.com) and place it in the project root directory.
3. Launch the Jupyter Notebook interface:
   ```bash
   jupyter notebook
   ```
4. Open your EDA notebook file and run the cells sequentially to reproduce the visualizations and observations.

## Project Structure
```text
├── train.csv                # Titanic dataset from Kaggle
├── titanic_eda.ipynb        # Notebook containing the main analysis and plots
└── README.md                # Project documentation
```

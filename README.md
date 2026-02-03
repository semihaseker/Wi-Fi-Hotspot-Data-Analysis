# 📶 Wi-Fi Hotspot Analysis & Classification

This project focuses on performing a comprehensive **Exploratory Data Analysis (EDA)** and building a **Machine Learning model** to analyze and classify Wi-Fi hotspots in various neighborhoods. The study covers the entire data science pipeline: from synthetic data generation and outlier handling to predictive modeling.

##  Project Objective

The goal is to understand the distribution of Wi-Fi services across different regions, handle data quality issues (outliers/missing values), and develop a **Logistic Regression** model to predict whether a hotspot is "Free" based on its technical and geographical attributes.

##  Tech Stack

* **Language:** Python
* **Libraries:** - `Pandas` & `NumPy` (Data Manipulation)
* `Matplotlib` & `Seaborn` (Data Visualization)
* `Scikit-learn` (Machine Learning & Preprocessing)



##  Key Features of the Analysis

The project includes several critical data processing steps:

1. **Synthetic Data Generation:** Simulating real-world scenarios with 200 observations and 6 attributes.
2. **Exploratory Data Analysis (EDA):**
* Statistical summaries and correlation checks.
* Analysis of Wi-Fi speeds across different providers and neighborhoods.


3. **Advanced Visualization:**
* Distribution plots for internet speeds.
* Geographical scatter plots showing hotspot density.
* Heatmaps for missing value detection.


4. **Data Cleaning:**
* **Outlier Detection:** Identified extreme speed values using **Boxplots**.
* **Handling Strategies:** Compared "Median Replacement" vs "Row Removal" methods.
* **Imputation:** Categorical missing values in the 'provider' column were handled using "Unknown" labeling.



## Machine Learning Model

A **Logistic Regression** classifier was implemented to distinguish between "Free" and "Paid/Limited" connections.

* **Preprocessing:** Label Encoding for categorical variables.
* **Evaluation:** The model achieves a significant recall rate for identifying free hotspots, demonstrating a complete end-to-end classification workflow.

## Project Structure

```bash
├── AID_Project.ipynb    # Main Jupyter Notebook containing all code and analysis
├── README.md            # Project documentation
└── (Data is generated within the notebook)

```

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/semihaseker/wifi-hotspot-analysis.git

```


2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```


3. Open `AID_Project.ipynb` in Jupyter Notebook or VS Code and run all cells.

## Contributors

* **Hana Bubalo**
* **Semiha Seker**

# Countries-Data-capstone-Project

# Global Countries Data Analysis Capstone 🌍

A data analysis project examining global demographics, political structures, and regional distributions using Python and Pandas. This notebook provides insights into population trends, democracy scores, and political leadership across different continents.

## 🚀 Key Insights & Analysis

This project performs a detailed exploratory data analysis (EDA) on the `Countries.csv` dataset, covering the following key areas:

* **Population Demographics:**
    * Identified countries with the **highest and lowest populations**.
    * Retrieved specific details (e.g., Capital Cities) for extreme population outliers.
    * Analyzed population distribution within specific continents (e.g., finding the most populous nation in **Africa**).
    
* **Political Analysis:**
    * Ranked the **Top 5 Countries** by Democracy Score.
    * Investigated political leadership, including identifying the leader of the 2nd most populous country.
    * Quantified data completeness by counting countries with unknown/missing political leaders.

* **Regional & Text Analysis:**
    * Analyzed the distribution of countries across different **Regions** (e.g., Eastern Europe).
    * Performed text-based filtering to count how many countries have **"Republic"** in their official long names.

## 🛠️ Tech Stack

* **Language:** Python 3.13.3
* **Library:** Pandas, NumPy
* **Environment:** Jupyter Notebook / Google Colab

## 📂 Project Structure

The analysis follows a structured approach:
1.  **Data Loading & Inspection:** Using `df.head()`, `df.info()`, and `df.describe()` to understand data quality.
2.  **Conditional Filtering:** Using boolean indexing (e.g., `df[df['region'] == 'Eastern Europe']`) to extract specific subsets.
3.  **Sorting & Ranking:** Utilizing `sort_values()` and `nlargest()` to find top performers.
4.  **String Manipulation:** Applying custom functions to search for keywords like "Republic" in country names.

## 💻 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/LakshayGarg/Countries-Data-Analysis.git](https://github.com/LakshayGarg/Countries-Data-Analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy
    ```
3.  **Run the Notebook:**
    Open `Data_Captsone_Project.ipynb` in Jupyter Notebook or Google Colab.
    *(Note: Ensure `Countries.csv` is in the same directory)*

## 👤 Author

**Lakshay Garg**
* [GitHub Profile](https://github.com/lakshayy05)

---
*This project is part of my Data Science Capstone series, focusing on real-world data manipulation and insight generation.*

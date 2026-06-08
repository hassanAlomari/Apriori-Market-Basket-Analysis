# 🛒 Market Basket Analysis: Uncovering Retail Purchasing Patterns

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Data Mining](https://img.shields.io/badge/Data%20Mining-Apriori-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red.svg)

## 📌 Project Overview
In the competitive retail sector, understanding customer purchasing behavior is critical for maximizing revenue and optimizing store layouts. This Data Mining project applies **Market Basket Analysis** using the **Apriori Algorithm** to discover hidden associations and patterns between products frequently bought together. 

The project goes beyond raw technical implementation by providing a comprehensive data story and actionable business recommendations, which are detailed in the accompanying presentation.

## 📊 Dataset Description
The analysis is based on a transactional dataset containing **20,508 records** of retail purchases. 

**Features:**
* `Transaction`: Unique identifier for each customer's transaction.
* `Item`: The specific product purchased.
* `date_time`: The exact timestamp of the transaction.
* `period_day`: Categorical representation of the time of day (e.g., Morning, Afternoon, Evening).
* `weekday_weekend`: Indicates whether the transaction occurred on a weekday or during the weekend.

## 🛠️ Methodology & Workflow
1. **Data Preprocessing & Cleaning:** Handling missing values, formatting datetime objects, and restructuring the data into a transactional matrix suitable for Association Rule Mining.
2. **Exploratory Data Analysis (EDA):** Visualizing top-selling items, identifying peak transaction hours, and analyzing purchasing trends across different days of the week.
3. **Association Rule Mining:** * Applying the **Apriori Algorithm** to generate frequent itemsets.
   * Extracting association rules based on critical evaluation metrics: **Support**, **Confidence**, and **Lift**.
4. **Data Storytelling:** Summarizing the mathematical outputs into strategic business language (available in the `.pptx` presentation).

## 💡 Key Business Insights & Applications
*(Note: Full strategic insights are available in the project presentation)*
* **Cross-Selling Opportunities:** Identifying pairs of items with high *Lift* scores to create targeted promotional bundles.
* **Store Layout Optimization:** Recommendations on placing high-confidence associated items adjacent to each other to increase spontaneous purchases.
* **Time-Based Promotions:** Utilizing the `period_day` and `weekday_weekend` features to schedule dynamic pricing and targeted marketing campaigns during peak specific hours.

## 📂 Repository Structure
```text
├── Apriori - Market Basket Analysis_fainal _new.ipynb   # Main notebook containing EDA and Apriori implementation
├── project_data_mining.pptx                             # Presentation slides with business insights
├── dataset.csv                                          # Transactional dataset (20,508 rows)
└── README.md                                            # Project documentation
ذ
```
## 🚀 How to Run
1. **Clone this repository to your local machine.**

2. **Ensure you have the required libraries installed (`pandas`, `matplotlib`, `seaborn`, `mlxtend` for `Apriori`).**

3. **Open the Jupyter Notebook to explore the code, visualizations, and rule generation processes.**

# Amazon Sale Analysis

This repository contains a comprehensive data analysis of an Amazon Sale Report. The analysis, performed using Python with libraries like Pandas, Matplotlib, and Seaborn, aims to extract key insights into customer behavior, popular products, fulfillment methods, and geographical sales distribution.

## Project Overview
The goal of this project is to analyze the provided Amazon Sale Report data to identify trends and patterns that can help in making informed business decisions. The analysis covers various aspects of the sales data, including:

- Data cleaning and preprocessing (handling missing values, correcting data types).

- Exploratory Data Analysis (EDA) to understand the distribution of key variables.

- Identifying top-selling products, preferred sizes, and customer demographics.

- Analyzing fulfillment methods and sales channels.

## Dataset
The analysis uses a CSV file named ```Amazon Sale.csv.```sql This dataset contains detailed information about individual orders, including:

- ```Order ID```

- ```Date```

- ```Status```

- ```Fulfilment```

- ```Sales Channel```

- ```Category```

- ```Size```

- ```Quantity```

- ```Amount```

- ```ship-city```

- ```ship-state```

- ```B2B``` (Business-to-Business) status

- And other relevant sales metrics.

## Analysis Highlights
The data analysis revealed several significant insights:

- **Customer Base:** The business has a significant customer base concentrated in Maharashtra state.

- **Buyer Type:** The majority of buyers (approximately 99.3%) are retailers, with a smaller percentage (0.7%) being B2B buyers.

- **Fulfillment:** Most orders are fulfilled directly by Amazon.

- **Product Demand:** There is a high demand for T-shirts, making it the top-selling product category.

- **Preferred Size:** M-Size is the most preferred choice among buyers across different categories.

These findings suggest opportunities for targeted marketing and inventory management strategies.

## Technologies Used
- **Python:** The primary programming language for data analysis.

- **Pandas:** For data manipulation and analysis.

- **Matplotlib:** For creating static, interactive, and animated visualizations.

- **Seaborn:** For creating informative and attractive statistical graphics.

## Setup and Usage
To run this analysis locally, follow these steps:

1. **Clone the repository:**
```
git clone https://github.com/your-username/amazon-sale-report-analysis.git
cd amazon-sale-report-analysis
```
2. **Ensure you have Python installed.** It's recommended to use a virtual environment.
```
python -m venv venv
source venv/bin/activate  # On Windows: `venv\Scripts\activate`
```
3. **Install the required libraries:**
```
pip install pandas matplotlib seaborn jupyter
```
4. **Place the** ```Amazon Sale.csv``` **file** in the root directory of the cloned repository.

5. **Open and run the Jupyter Notebook:**
```
jupyter notebook "Amazon Sale Report (1).ipynb"
```
This will open the Jupyter Notebook in your web browser, where you can execute the cells to see the analysis and visualizations.

## Conclusion
The data analysis provides a clear picture of the Amazon sales performance, highlighting key areas such as customer demographics, product popularity, and operational efficiency. These insights can be leveraged to optimize sales strategies, improve customer targeting, and enhance overall business growth.

🥘 zomato-data-analysis
Zomato Restaurant Data Analysis using Python & Pandas

📌 Overview
This project explores and analyzes restaurant data from Zomato using Python. It focuses on extracting insights related to locations, cuisines, ratings, and cost. It includes data cleaning, exploratory data analysis (EDA), and visualizations to discover patterns and trends in the restaurant industry.

<img width="1038" height="728" alt="Screenshot 2025-07-31 124718" src="https://github.com/user-attachments/assets/1d8cf525-3d84-4bd3-870d-9f0c5f331ddb" />

⚙️ Methodology & Working
1. Data Loading
Load the Zomato dataset (CSV format).

<img width="1029" height="636" alt="Screenshot 2025-07-31 124731" src="https://github.com/user-attachments/assets/53b9703f-1248-4f25-a6da-945dee559699" />

Inspect basic structure: number of rows, columns, data types.

2. Data Preprocessing
Handle missing values in key fields like rating, cuisine, location.

Drop irrelevant or redundant columns (e.g., URL, address, phone).

Convert categorical variables (like 'online_order', 'book_table') to binary numeric format.

Clean columns like 'rate' and 'cost' by removing special characters and converting to float/integer.

Remove outliers using Z-score or IQR method.

<img width="1041" height="713" alt="Screenshot 2025-07-31 124756" src="https://github.com/user-attachments/assets/f1d67049-fb95-4bb9-9c90-6d36c28ac4a4" />


3. Exploratory Data Analysis (EDA)
Top cuisines, top-rated restaurants, cost distributions, online orders, table booking.

Analysis based on city, rating, cost, and votes.

Visualization using matplotlib and seaborn.

4. Visualization
Barplots for most common cuisines, cities, and ratings.

Pie charts for online order/book table availability.

Correlation heatmap for numerical features.

📊 Key Insights
Bengaluru has the highest number of restaurants in the dataset.

North Indian is the most common cuisine served.

Online orders are more popular in cities like Bengaluru and Delhi NCR.

Higher-rated restaurants are often in premium locations and tend to offer table booking.

There's a moderate correlation between votes and rating.

🔍 Visualizations
✅ Cuisine Distribution
✅ Online Order vs Book Table Analysis
✅ Top Locations with Most Restaurants
✅ Ratings Distribution
✅ Heatmap for Correlations
✅ Cost Analysis across Cities

📁 Dataset
Source: Zomato India Restaurant Data (Kaggle)
https://www.kaggle.com/code/akshitmadan/zomato-data-set-analysis-visualization/input

Features: restaurant name, location, cuisines, average cost, online order availability, rating, etc.

🚀 Installation
bash
Copy
Edit
git clone https://github.com/krzhnaa/Zomato(data science).git
cd zomato-data-analysis
install required libraries
▶️ Usage
Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook "zomato analysis.ipynb"
📦 Requirements
Python 3.7+

pandas

numpy

seaborn

matplotlib

scipy (for outlier detection)

🔮 Future Enhancements
Add interactive dashboard using Streamlit or Plotly Dash.

Predict restaurant ratings using ML (regression/classification).

Cluster locations or cuisines using unsupervised ML.

Integrate live data from Zomato’s API (if available).

🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

🏡 Airbnb Data Cleaning & Exploratory Data Analysis (EDA)

This project focuses on data cleaning and exploratory data analysis (EDA) of Airbnb listings.
The goal is to showcase practical data wrangling, visualization, and storytelling skills that are essential for Data Analyst roles.

📌 Project Workflow

🔹 Step A: Import & Understand Data

Loaded the Airbnb dataset.

Inspected shape, column info, and summary statistics.

🔹 Step B: Data Cleaning

Handled missing values:

Filled numerical columns (bathrooms, bedrooms, beds, review_scores_rating) with median.

Filled categorical column (neighbourhood) with most common value.

Replaced missing host_response_rate with "Unknown".

Converted host_since, first_review, last_review to proper datetime.

Removed duplicates.

Handled outliers in log_price (trimmed to 1st–99th percentile).

Dataset reduced from 74,111 → 72,651 rows.

🔹 Step C: Exploratory Data Analysis (EDA)

Distribution of room types and property types.

Price trends across neighbourhoods.

Relationship between accommodates (guest capacity) and price.

Correlation between review scores and price.

Heatmap of numerical correlations.

🔹 Step D: Before & After Cleaning

Compared price distributions before and after cleaning.

Outlier removal significantly reduced unrealistic prices.

### 🔹 Step E: Insights & Storytelling

1. **Room Type & Pricing**
   - Private rooms are most affordable → budget travelers.  
   - Entire homes/apartments are more premium → families, groups.  
   ![Room Type Pricing](https://github.com/KIRANRW9/Airbnb-EDA/blob/repo-exercise/room_type_price.png)

2. **Neighbourhood Trends**
   - Central/touristy neighbourhoods have higher average prices.  
   ![Neighbourhood Boxplot](https://github.com/KIRANRW9/Airbnb-EDA/blob/repo-exercise/neighbourhood_boxplot.png)

3. **Reviews & Ratings Influence**
   - Higher review scores and more reviews correlate with higher prices.  
   ![Reviews vs Price](https://github.com/KIRANRW9/Airbnb-EDA/blob/repo-exercise/reviews_price.png)

4. **Effect of Cleaning**
   - Before cleaning → heavy skew due to extreme luxury outliers.  
   - After cleaning → smoother distribution, realistic price range.  
   ![Before After Cleaning](https://github.com/KIRANRW9/Airbnb-EDA/blob/repo-exercise/before_after_price.png)

##  Dataset
The full dataset (98 MB) is available on Kaggle:
[Air-bnb dataset](https://www.kaggle.com/datasets/sankalp102/air-bnb)

## 📂 Repository Structure

```
Airbnb-EDA/
┣ 📓 notebooks/ # Jupyter Notebook
┣ 🖼️ images/ # Saved visualization PNGs
┣ 📊 data/ # dataset
┣ 📄 README.md
┗ 📦 requirements.txt
```


🛠️ Tech Stack & Libraries

Python

Pandas, NumPy → Data Cleaning & Wrangling

Matplotlib, Seaborn → Data Visualization

Google Colab → Development Environment

🚀 How to Run

Clone the repository:

git clone https://github.com/KIRANRW9/Airbnb-EDA.git


Open the Jupyter/Colab notebook:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KIRANRW9/Airbnb-EDA/blob/master/Airbnb.ipynb)


Airbnb.ipynb


Run all cells to reproduce cleaning and analysis.

👉 Or open directly in Google Colab.

🎯 Key Learnings

Hands-on experience in real-world data cleaning.

Built visualizations for insightful storytelling.

Demonstrated how outlier handling improves analysis quality.

📌 Next Steps (Future Work)

Build a predictive model for Airbnb pricing.

Analyze seasonal trends in bookings.

Create an interactive dashboard (Tableau/Power BI).

👤 Author

Kiran Rangu

📧 kiranrw09@gmail.com

🌐 www.linkedin.com/in/kiranrangu

🔗 https://github.com/KIRANRW9

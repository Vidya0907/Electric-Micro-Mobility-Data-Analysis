# 🚲 Electric-Micro-Mobility-Data-Analysis 

<br/>

## ❓ Problem Statement  
Yulu, a bike-sharing company, wants to **understand the key factors affecting rental demand** in order to:  
- Optimize fleet availability across different seasons and weather conditions  
- Increase customer satisfaction by predicting demand patterns  
- Design targeted promotions for weekends, holidays, and peak seasons  

## ✅ Solution Approach  
We conducted an **Exploratory Data Analysis (EDA) with statistical hypothesis testing** on the Yulu dataset to:  
- Clean and preprocess the data (nulls, duplicates, outliers)  
- Explore demand patterns by season, weather, and working day  
- Perform **statistical tests (T-test, Levene’s, Kruskal-Wallis, Chi-square)** to validate differences in demand  
- Visualize correlations and distributions to identify strong predictors of rental count  
- Provide actionable business insights for decision-making  



## 🛠️ Tools & Libraries
- **Python**  
- **Pandas, NumPy** – Data handling  
- **Matplotlib, Seaborn** – Visualization  
- **SciPy** – Statistical hypothesis testing  



## 🔍 Analysis Workflow
1. **Data Import & Cleaning**
   - Loaded dataset (`yulu.csv`)  
   - Checked data types, null values, and duplicates  
   - Created new features (e.g., `quarter` from datetime)  
   - Outlier detection using **IQR method**

2. **Exploratory Data Analysis (EDA)**
   - Frequency plots for categorical variables (`season`, `holiday`, `workingday`, `weather`)  
   - Distribution plots (temperature, humidity, windspeed, rentals, etc.)  
   - Boxplots to identify outliers and spread of features  
   - Correlation heatmap  

3. **Statistical Tests**
   - **T-Test** → Compared demand between weekdays vs weekends  
   - **Levene’s Test** → Checked variance equality across groups  
   - **Kruskal-Wallis Test** → Checked if demand differs significantly across seasons & weather conditions  
   - **Chi-Square Test** → Examined relationship between weather and season  



## 📊 Key Insights
- ✅ **Weekend vs Weekdays**: Significant difference in demand → Rentals are higher on weekends.  
- ✅ **Weather Effect**: Poor weather significantly reduces rentals.  
- ✅ **Seasonality**: Rental demand varies across seasons (higher in summer/autumn).  
- ✅ **Correlation**: Strong correlation between `temperature`, `atemp`, and rental counts.  


## 📈 Visualizations
- Count plots for season, holiday, working day, weather  
- Histograms & KDE plots for numerical features  
- Boxplots to detect outliers in rental counts and features  
- Correlation heatmap to identify strong relationships  
- Distribution plots comparing rental demand across seasons & weather  




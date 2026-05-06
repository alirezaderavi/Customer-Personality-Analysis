# 🧠 Customer Personality Analysis

A data science project for clustering and understanding customer behavior using unsupervised machine learning techniques.


## 📌 Overview
Customer Personality Analysis is a detailed analysis of a company's ideal customers. This project helps businesses better understand their customers and allows them to tailor products to the specific needs, behaviors, and concerns of different customer segments.
By performing customer segmentation, businesses can target the right audience, optimize marketing campaigns, and boost overall revenue.

## 🎯 Objectives

Perform Exploratory Data Analysis (EDA) to uncover patterns and distributions in customer data
Clean and preprocess raw customer data for modeling
Apply unsupervised clustering algorithms to segment customers into meaningful groups
Profile each customer cluster to derive actionable business insights
Recommend targeted marketing strategies for each segment


## 📂 Dataset
This project uses the Customer Personality Analysis dataset from Kaggle.
Key features include:
CategoryFeaturesDemographicsAge, Education, Marital Status, Income, Number of ChildrenProductsSpending on Wines, Fruits, Meat, Fish, Sweets, GoldPromotionsResponses to marketing campaigns (1–5), Discounts acceptedChannelsPurchases via Web, Catalog, Store, Number of web visits

## 🛠️ Tech Stack

Python 3.x
Pandas — data manipulation
NumPy — numerical computation
Matplotlib / Seaborn — data visualization
Scikit-learn — preprocessing, PCA, clustering (KMeans / Agglomerative)
Jupyter Notebook — interactive development environment


## 🔍 Methodology

Data Cleaning — Handle missing values, remove outliers, engineer new features (e.g., Age, Total Spending, Children)
EDA — Visualize distributions, correlations, and customer behaviors
Feature Engineering — Encode categorical variables, scale numeric features
Dimensionality Reduction — Apply PCA to reduce feature space
Clustering — Use KMeans or Agglomerative Clustering to identify customer segments
Cluster Profiling — Analyze and interpret each cluster's characteristics


## 📊 Key Findings

Customers are primarily segmented into groups based on income level and spending behavior
High-income customers show stronger response to premium product promotions
Customers without children tend to spend significantly more per transaction
Wine and Meat are the top-selling product categories across all segments
In-store purchases are the preferred channel, followed by web and catalog


## 🚀 Getting Started
Prerequisites
bashpip install pandas numpy matplotlib seaborn scikit-learn jupyter
Run the Notebook
bashgit clone https://github.com/alirezaderavi/Customer-Personality-Analysis.git
cd Customer-Personality-Analysis
jupyter notebook customer-personality-analysis.ipynb

## 📥 Download the dataset from Kaggle and place it in the project directory.


## 📈 Results & Business Recommendations
ClusterProfileRecommendationHigh ValueHigh income, high spending, no childrenTarget with premium offers & loyalty programsMid-TierAverage income, moderate spendingUpsell with bundles and discount campaignsBudget-ConsciousLow income, price-sensitivePromote deals, coupons, and affordable optionsInactiveLow engagement, infrequent purchasesRe-engage with personalized email campaigns

## 📁 Project Structure
Customer-Personality-Analysis/
│
├── customer-personality-analysis.ipynb   # Main analysis notebook
└── README.md                             # Project documentation

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License
This project is open-source and available under the MIT License.

## 👤 Author
Alireza Deravi

If you found this project helpful, please consider giving it a ⭐

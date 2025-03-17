# Google Play Store Apps - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Google Play Store Apps** dataset. The goal is to analyze the characteristics of apps, identify trends, and gain insights into the most popular categories, ratings, reviews, and pricing strategies.

## 📂 Dataset Information
- **Dataset Name**: Google Play Store Apps Dataset
- **Number of Entries**: 
- **Features**:
  - App Name
  - Category
  - Rating
  - Reviews
  - Size
  - Installs
  - Type (Free/Paid)
  - Price
  - Content Rating
  - Genres
  - Last Updated
  - Current Version
  - Android Version

## 🛠️ Key Steps in Analysis
1. **Data Cleaning**
   - Identified and handled missing values
   - Removed duplicate records
2. **Descriptive Statistics**
   - Summary statistics of numeric features
   - Distribution of app ratings, reviews, and installs
3. **Feature Analysis**
   - Most popular app categories
   - Skewness of rating, reviews, size, installs, and price
4. **Correlation Analysis**
   - Relationship between app rating and reviews
   - Pricing trends among app categories
5. **Visualization Techniques Used**
   - Histograms, boxplots, bar charts, and scatter plots

## 📊 Key Observations & Findings
- **The dataset contains missing values and duplicate records**, which were cleaned.
- **Rating and year features are left-skewed**, while **reviews, size, installs, and price are right-skewed**.
- **Family and Games categories dominate the Play Store**, accounting for 18% and 11% of apps, respectively.
- **Beauty, Comics, and Arts categories have the least number of apps**.
- **Paid apps are significantly fewer compared to free apps**, suggesting that most apps follow an ad-supported revenue model.

## 💻 Technologies Used
- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Seaborn 🎨
- Jupyter Notebook 📒

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/ricashukla/Playstore-EDA.git
   cd Playstore-EDA
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run `Playstore EDA.ipynb`

## 🔥 Future Work
- Predict app success based on features such as category, price, and reviews.
- Extend the analysis to include sentiment analysis on user reviews.
- Develop a dashboard for interactive exploration of Play Store data.

---
✨ **If you find this project useful, give it a ⭐ on GitHub!**

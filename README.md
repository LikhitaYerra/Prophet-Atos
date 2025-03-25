# BAYC Analysis and Forecasting

## 📌 Project Overview

This project focuses on analyzing and forecasting the trends of the **Bored Ape Yacht Club (BAYC)** NFT collection. We leverage historical data to gain insights into price movements and predict future trends using advanced time series forecasting techniques.

## 📂 Files in This Repository

- `BAYC.ipynb` – Exploratory Data Analysis (EDA) and data preprocessing.
- `ProphetBAYC.ipynb` – Time series forecasting using **Facebook Prophet**.
- `combined_df.csv` – Cleaned dataset for analysis.
- `predicted_values.csv` – Output of the Prophet model's forecast.

## 🔍 Analysis & Methodology

### 1️⃣ Data Collection & Cleaning

- The dataset consists of historical **BAYC NFT** prices and transaction data.
- Cleaning includes handling missing values, outliers, and feature engineering.

### 2️⃣ Exploratory Data Analysis (EDA)

- Trend analysis of **floor prices, sales volume, and market cap**.
- Distribution and correlation study of key metrics.
- Visualization of historical price trends.

### 3️⃣ Forecasting with Prophet

- **Facebook Prophet** is used for time series prediction.
- It captures **seasonality, trends, and holiday effects**.
- Output stored in `predicted_values.csv`.

## 📊 Key Findings

- The **floor price trend** follows a cyclical pattern with peaks and dips.
- Market activity correlates with broader crypto trends and macroeconomic events.
- The **Prophet model** provides reasonable predictions but can be fine-tuned with additional external factors.

## ⚡ How to Use

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/BAYC-Analysis.git
   cd BAYC-Analysis
   ```
2. **Install dependencies** (Recommended: Create a virtual environment)
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Jupyter notebooks**
   ```sh
   jupyter notebook
   ```
4. **Load ****`ProphetBAYC.ipynb`** to visualize and analyze forecasts.

## 🔧 Future Improvements

- Incorporate **macro-financial indicators** like Ethereum prices and stock market trends.
- Explore **Deep Learning models** like LSTMs for improved forecasting.
- Build a **dashboard** for real-time analysis of NFT market trends.

##

## 📩 Contact

For any questions or collaborations, feel free to reach out!

---

Made with ❤️ by [Your Name]


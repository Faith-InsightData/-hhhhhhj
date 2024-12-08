# 📊 **Bitcoin Price Analysis Project**  

## 🌟 **Overview**  
This project delves into the historical analysis of Bitcoin price trends over time. By utilizing Python and powerful libraries like `pandas` and `matplotlib`, the project focuses on cleaning, processing, and analyzing Bitcoin price data. The analysis includes trends on a **monthly**, **quarterly**, and **yearly** basis. Additionally, this project showcases how to effectively clean data, handle missing values, and present insights visually.

---

## 🛠️ **Setup Instructions**  

### Prerequisites  
Ensure you have the following installed:  
- Python 3.7+
- Libraries: `pandas`, `matplotlib`, and `numpy`

### Installation Steps  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/bitcoin-analysis.git
   cd bitcoin-analysis
   ```
2. Install dependencies:  
   ```bash
   pip install pandas matplotlib numpy
   ```
3. Download the dataset and place it in the project directory. Ensure the dataset is named:  
   `bitcoin_price_Training - Training.csv`

---

## 📚 **Data Description**  
The dataset consists of 7 columns:  

| **Column**       | **Description**                                                                 |
|-------------------|---------------------------------------------------------------------------------|
| `Date`           | Date of the record, formatted as `Month Day, Year`                             |
| `Open`           | Opening price of Bitcoin on that date                                          |
| `High`           | Highest price of Bitcoin on that date                                          |
| `Low`            | Lowest price of Bitcoin on that date                                           |
| `Close`          | Closing price of Bitcoin on that date                                          |
| `Volume`         | Total volume of Bitcoin traded (in USD)                                        |
| `Market Cap`     | Market capitalization of Bitcoin (in USD)                                      |

---

## 🔄 **Step-by-Step Workflow**  

### 1️⃣ **Data Cleaning & Preparation**  
- **Transformations**:  
  - Cleaned `Volume` and `Market Cap` columns by removing commas and replacing invalid values like `'-'`.  
  - Converted `Volume` and `Market Cap` to numeric data types.
  - Converted `Date` column to `datetime` format and set it as the index.

### 2️⃣ **Resampling and Analysis**  
- Resampled the data into **monthly**, **quarterly**, and **yearly** intervals.  
- Calculated key statistics for the `Close` price, including:  
  - **Mean**: Average closing price  
  - **Min**: Minimum closing price  
  - **Max**: Maximum closing price  

### 3️⃣ **Visualization**  
- Generated line plots to visualize trends in the closing price over different time intervals:  
  - **Yearly Closing Price**  
  - **Quarterly Closing Price**  
  - **Monthly Closing Price**  

---

## 📈 **Key Findings**  
- Bitcoin's closing price exhibits seasonal and cyclical patterns.
- Higher volatility can be observed in quarterly and monthly trends.
- Average prices vary significantly between years, reflecting market sentiment.

---

## 🔍 **Usage**  
### Running the Code  
1. Open the script in your preferred IDE or Jupyter Notebook.  
2. Update the file path for the dataset if necessary:  
   ```python
   file_path = '/content/bitcoin_price_Training - Training.csv'
   ```
3. Execute the script to analyze and visualize data.  

---

## 📊 **Sample Output**  

### Example Statistics for Quarterly Closing Prices:  
| Quarter       | Mean Price (USD) | Min Price (USD) | Max Price (USD) |  
|---------------|------------------|-----------------|-----------------|  
| Q1 2017       | $900.00          | $850.00         | $1100.00        |  
| Q2 2017       | $1500.00         | $1200.00        | $2000.00        |  

---

## 🎨 **Features**  
- 📅 **Date Resampling**: Analyze Bitcoin prices across different intervals.  
- 📊 **Visualization**: Interactive plots for insightful trends.  
- 🧹 **Data Cleaning**: Robust handling of missing and invalid data.  

---

## 🙌 **Contributions**  
Contributions, issues, and feature requests are welcome! Feel free to:  
- Fork the project  
- Open a pull request  

---

## 📜 **License**  
This project is licensed under the MIT License. See the `LICENSE` file for details.  

---

## 🎉 **Acknowledgments**  
- Data Source: Provided by [Insert Data Provider Name].  
- Inspired by the growing interest in cryptocurrency analytics.  

**🚀 Happy Analyzing!**  

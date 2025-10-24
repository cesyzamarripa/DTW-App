# 📈 DTW Stock Analyzer

Compare two time windows of stock price data using Dynamic Time Warping (DTW). This project uses real Google stock data to demonstrate time series similarity analysis.

---

## 🔧 Features

- Upload any stock CSV with columns: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`
- Select two time windows for comparison
- Run DTW analysis using FastDTW and Euclidean distance
- Visualize alignment between time series
- Get plain-language insights on similarity

---

## 🚀 How to Use

1. Open `notebook.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Upload your CSV file (e.g., `GOOG.csv`)
3. Modify the date ranges in **Step 4** to define your comparison windows
4. Run all cells to see:
   - DTW distance
   - Alignment path
   - Visualization
   - Summary insights

---

## 📊 Example Output

![DTW Alignment Plot]

---

## 📘 About DTW

Dynamic Time Warping (DTW) is a technique for measuring similarity between time series that may vary in speed or length. It’s widely used in:

- Finance (stock comparisons)
- Speech recognition
- Pattern matching
- Sensor data analysis

This project uses **FastDTW**, an efficient approximation of DTW, to compare stock prices across different time windows.

---

## 📁 Repo Structure


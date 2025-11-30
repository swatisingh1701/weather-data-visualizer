# 🌦 Weather Data Visualizer

**Mini Project – Programming for Problem Solving using Python**
**Author:** Swati Singh
**Roll No:** 2501730269

---

## 📌 Project Overview

This project analyzes real-world weather data and visualizes important climate parameters such as temperature, humidity, and rainfall. It demonstrates data cleaning, statistical computation, and graphical visualization using **Pandas, NumPy, and Matplotlib**.

The goal is to understand patterns in daily and monthly weather trends and present them through clean and meaningful plots.

---

## 📂 Features Implemented

### ✔ 1. Data Loading

* Loaded CSV weather dataset
* Inspected structure using `head()`, `info()`, `describe()`

### ✔ 2. Data Cleaning

* Removed invalid/missing date values
* Filled missing numeric data using mean
* Selected important columns:
  `date`, `temperature`, `rainfall`, `humidity`

### ✔ 3. Statistical Analysis

Using **NumPy**:

* Mean
* Minimum
* Maximum
* Standard Deviation

### ✔ 4. Data Grouping

Grouped by `month` to calculate:

* Monthly average temperature
* Monthly rainfall total
* Monthly average humidity

### ✔ 5. Visualization

Created using **Matplotlib**:

* 📈 Daily Temperature Line Plot
* 📊 Monthly Rainfall Bar Chart
* 🔵 Humidity vs Temperature Scatter Plot
* 🖼 Combined Two-Plot Figure

All plots are exported as PNG images.

---

## 📊 Output Files

The following files are generated:

| File Name                  | Description                                 |
| -------------------------- | ------------------------------------------- |
| `daily_temperature.png`    | Daily temperature trend                     |
| `monthly_rainfall.png`     | Total rainfall per month                    |
| `temp_vs_humidity.png`     | Relationship between temperature & humidity |
| `combined_plot.png`        | Combined subplot visualization              |
| `cleaned_weather_data.csv` | Cleaned dataset                             |
| `summary_report.txt`       | Summary of insights                         |

All images are located inside the **plots/** folder.

---

## 📁 Project Structure

```
weather-data-visualizer/
│── weather_visualizer.py
│── weather_data.csv
│── cleaned_weather_data.csv
│── summary_report.txt
│── README.md
│── plots/
│      ├── daily_temperature.png
│      ├── monthly_rainfall.png
│      ├── temp_vs_humidity.png
│      ├── combined_plot.png
```

---

## 🧠 Key Insights from the Data

* Temperature shows daily fluctuations across the month
* Rainfall varies significantly and forms month-wise peaks
* Humidity has a noticeable trend when compared with temperature
* Visualization helps understand seasonal and monthly weather behavior

---

## 🔧 Technologies Used

* **Python 3**
* **Pandas** for data cleaning
* **NumPy** for statistics
* **Matplotlib** for visualization

---

## 📜 How to Run

1. Install required libraries:

   ```
   pip install pandas numpy matplotlib
   ```
2. Run the script:

   ```
   python weather_visualizer.py
   ```
3. Check the output inside the `plots` folder.

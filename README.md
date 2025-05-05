# Electric Vehicle Data Analysis Using Python

## 🌟 Project Overview
This project analyzes a comprehensive dataset of electric vehicles (EVs) to uncover insights about pricing, performance, battery efficiency, and more. The analysis includes data filtering, outlier detection, relationship visualization, a recommendation system, and hypothesis testing to compare EV manufacturers.

## 📂 Dataset
The dataset (`FEV-data-Excel.xlsx`) contains the following key attributes:
- **Manufacturer (Make)** and model details
- **Pricing** (Minimal price in PLN)
- **Performance metrics** (Engine power, torque, acceleration)
- **Battery specifications** (Capacity, range, charging power)
- **Physical dimensions** (Length, width, height, weight)
- **Energy consumption** (kWh/100 km)

## 🛠️ Tools & Libraries
- **Python** (Primary language)
- **Pandas** (Data manipulation)
- **NumPy** (Numerical operations)
- **Matplotlib & Seaborn** (Data visualization)
- **SciPy** (Statistical testing)
- **Jupyter Notebook** (Interactive analysis)

## 📋 Tasks & Implementation

### 1️⃣ **Task 1: Filtering EVs by Budget and Range**
- **Objective:** Identify EVs within a budget of 350,000 PLN and a minimum range of 400 km.
- **Key Findings:**
  - 12 EVs met the criteria from manufacturers like Tesla, Audi, and Volkswagen.
  - Audi had the highest average battery capacity (95 kWh), while Hyundai and Kia offered more affordable options.

### 2️⃣ **Task 2: Outlier Detection in Energy Consumption**
- **Method:** Interquartile Range (IQR) analysis.
- **Result:** No outliers detected, indicating consistent energy consumption across EVs.

### 3️⃣ **Task 3: Battery Capacity vs. Range Analysis**
- **Visualization:** Scatter plot with correlation analysis.
- **Insight:** Strong positive correlation (r = 0.81) between battery capacity and range. Tesla vehicles showed exceptional range efficiency.

### 4️⃣ **Task 4: EV Recommendation System**
- **Implementation:** A Python class (`EVRecommender`) that recommends top 3 EVs based on user inputs (budget, range, battery capacity).
- **Example Output:** For a budget of 300,000 PLN, desired range of 400 km, and battery capacity of 70 kWh, the system recommended:
  1. Volkswagen ID.3 Pro S
  2. Volkswagen ID.4 1st
  3. Tesla Model 3 Long Range

### 5️⃣ **Task 5: Hypothesis Testing (Tesla vs. Audi)**
- **Objective:** Compare average engine power between Tesla and Audi EVs.
- **Method:** Two-sample t-test.
- **Result:** No statistically significant difference (p-value = 0.1068).

## 📊 Key Insights
- **Budget-Friendly EVs:** Hyundai and Kia offer the most affordable options meeting the 400 km range requirement.
- **Range Efficiency:** Tesla provides the best range relative to battery size.
- **Performance Parity:** Engine power is comparable between Tesla and Audi.
- **Energy Efficiency:** No outliers suggest industry-wide standardization in energy consumption.

## 🚀 Recommendations
1. **For Consumers:** Tesla and Volkswagen offer the best range per PLN spent.
2. **For Manufacturers:** Highlight efficiency in marketing, especially for brands with smaller battery capacities.
3. **Future Work:** Expand analysis to include charging infrastructure and total cost of ownership.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


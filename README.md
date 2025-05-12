# IndiaRoadAccidentAnalysis

# 🚧 India Road Accident Data Analysis

This project explores a real-world dataset of over 12,000 road accident cases across India to uncover trends and patterns using Exploratory Data Analysis (EDA). The goal is to identify the critical factors contributing to road accidents and generate actionable insights to improve traffic safety.

---

## 📁 Dataset Overview

- **File:** Road.csv  
- **Rows:** 12,316  
- **Columns:** 32  
- **Attributes include:**  
  - Time of accident  
  - Day of week  
  - Driver's age and experience  
  - Vehicle type  
  - Cause of accident  
  - Severity (Slight, Serious, Fatal)

---

## 🧹 Data Cleaning Steps

- Removed duplicate rows (7 duplicates found)
- Handled missing values using:
  - Mode imputation for categorical variables
  - Replacement of unknown categories (e.g. 'Lorry (41?100Q)' → 'Lorry')
- Formatted time column to `HH:MM` for hourly analysis
- Engineered new features like `Time_HHMM` for visual analysis
- Standardized categorical values for better readability

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Key Visualizations
- **Bar Charts**: Distribution of accident severity, day of week, and vehicle types
- **Pie Charts**: Severity breakdown, driver age band distribution
- **Line Plot**: Accidents over time (peak during 5–6 PM)
- **Box Plot**: Accident severity by hour of day
- **Sunburst Chart**: Hierarchical view of accident severity by weekday

### 🔍 Insights

- Majority of accidents led to **slight injuries**, followed by serious and fatal ones.
- **Evening hours (5 PM to 6 PM)** had the highest number of accidents.
- **Weekends**, especially **Saturday and Sunday**, saw a noticeable spike.
- **Automobiles** were the most involved vehicle type.
- Drivers aged **18–50** were most prone to accidents.
- **Vehicle-to-vehicle collisions** caused the highest number of injuries.

---

## 📦 Technologies Used

- **Python**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Plotly** for interactive charts
- **Jupyter Notebook**

---

## 💬 What I Learned

- Practical skills in cleaning and analyzing large real-world datasets
- How to handle messy categorical data
- Importance of time-based and categorical EDA in transportation datasets
- Communicating insights through clear visualizations

---

## 📌 Future Enhancements

- Add correlation analysis to identify strongest predictors of accident severity
- Create a dashboard in Power BI or Tableau
- Integrate external weather or traffic datasets for deeper analysis

---

## 🧠 Author

**Kartik Parasher**  
*Aspiring Data Analyst | BBA Graduate | Passionate about turning data into insights*

---

## 📄 License

This project is for educational purposes only. Data belongs to its respective owners.


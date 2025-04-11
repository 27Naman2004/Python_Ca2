# 🔌 Electricity Consumption Analysis (With Streamlit App Version)

This project explores and visualizes electricity consumption patterns using an interactive **Streamlit web application**. It allows users to explore trends, relationships, and anomalies in electricity usage through a user-friendly interface.

---

## 📁 Dataset
The dataset used is `CDCF.csv`, which contains the following key columns:

- **Circle**
- **Division**
- **SubDivision**
- **Area**
- **Units**
- **Load**
- **Total Services**
- **Billed Services**
- **Category Description**
- **Month** *(if available)*

---

## 🎯 Objectives
The Streamlit app supports analysis for the following objectives:

1. **Relationship between Load and Units Consumed**
2. **Top 10 Areas with the Highest Electricity Consumption**
3. **Comparison of Billed Services vs Total Services**
4. **Electricity Consumption by Circle**
5. **Distribution of Billed Services**
6. **Electricity Consumption by Consumer Category**
7. **Distribution of Electrical Load**
8. **(Optional)** Monthly Trend of Electricity Consumption (if data is available)

Users can interactively select these objectives from dropdowns or sidebars in the app.

---

## 📊 Visualizations Included
The following types of visualizations are available:

- **Bar Plot**: Electricity consumption by Circle
- **Scatter Plot**: Total Services vs Billed Services
- **Histogram**: Distribution of Load
- **Bar Chart**: Electricity usage by Consumer Category
- **Heatmap**: Correlation between Units, Load, Services, etc.
- **Bar Chart**: Top 10 Areas by electricity consumption
- **Line Plot** *(optional)*: Monthly electricity usage trend
- **Box Plot**: Distribution of Billed Services
- **Scatter Plot**: Relationship between Load and Units

---

## 🧹 Data Cleaning & Preprocessing
The following preprocessing steps are performed:

- Missing values are handled via **mean**, **median**, or **custom value** (user-selectable)
- Columns are cast to proper data types
- Duplicate records are removed
- Column names are simplified where necessary
- Filters for categories and top areas for clean and informative visuals

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit** – for building the interactive UI
- **Pandas** – for data loading and manipulation
- **Matplotlib** – for visualizations
- **Seaborn** – for advanced visualizations and styling

---

## ▶️ How to Run

1. Install the required packages:
   ```bash
   pip install pandas matplotlib seaborn streamlit
   ```

2. Run the app:
   ```bash
   streamlit run app.py
   ```

3. Use the sidebar and dropdowns to select the type of analysis or visualization.

---

## 📌 Conclusion
This app makes electricity consumption analysis simple and accessible. It reveals:

- Which regions and areas consume the most electricity
- The relationship between load and units
- Gaps between billed and total services
- Differences across consumer categories

Useful for:
- Policy makers
- Electricity boards
- Data analysts
- Students exploring data science



# Los Angeles Crime Dashboard (2023–2025)

This Power BI project analyzes crime data in Los Angeles, focusing on patterns across victim demographics, crime types, geographic locations, and time trends. The goal is to visualize public safety data to help law enforcement, researchers, and the general public understand key areas of concern and take data-driven action.

---

## 🛠 Tools Used

- Microsoft Excel / Power Query for preprocessing
- Power BI for data modeling and interactive dashboard

---

## 📁 Dataset

- **Source:** [Los Angeles Open Data](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/data_preview)
- **Fields Included:**
  - Date and time of crime occurrence
  - Reported date
  - Crime type and crime codes
  - Weapon used (codes and descriptions)
  - Victim age, gender, and ethnicity
  - Location details (area, premise, address, coordinates)
  - Investigation status (solved/unsolved)

---

## 🔄 Steps Followed

### 1. Data Cleaning in Excel
- Replaced coded values with readable labels
- Formatted date and time columns for consistency

### 2. Data Preprocessing in Power Query
- Removed blanks, duplicates, and inconsistencies
- Converted columns to appropriate data types
- Standardized category labels

### 3. Data Modeling in Power BI
- Created relationships and hierarchies
- Added calculated columns and summary tables

### 4. Dashboard Creation in Power BI
- Built DAX measures for KPIs and calculations
- Designed slicers for year, crime type, and seriousness
- Created interactive visuals:
  - Time-series line graphs
  - Bar and column charts by age and location
  - Tree maps by ethnicity and gender
  - Donut charts for crime type, weapons used, and investigation status
  - Interactive map of crime locations

---

## 📊 Key Insights

- **Downtown** is consistently the most affected area
- Most crimes occur in the **early afternoon**
- **Firearms** are involved in a large portion of serious crimes
- Over **80% of crimes remain unsolved**
- Victims aged **31–50** are the most impacted group
- **Hispanic/Latino males** are disproportionately affected

---

![LA-Crime-1](https://github.com/user-attachments/assets/648d5822-4db4-4513-8bec-78b3e12c28f4)


---

![LA-Crime-2](https://github.com/user-attachments/assets/98ff0dad-6d62-4b9f-986a-e8d0b85f6588)


---


## 📦 Files Included

| File Name                  | Description                            |
|---------------------------|----------------------------------------|
| `LA-Crime-Data.pbix`      | Cleaned dataset used for modeling      |
| `LA-Crime-Dashboard.pbix` | Final interactive Power BI dashboard   |

---

## 🚀 How to Use

1. Open `LA-Crime-Data.pbix` to review the cleaned and modeled data.
2. Open `LA-Crime-Dashboard.pbix` in Power BI Desktop to interact with the dashboard.
3. Use the **slicers** to filter by:
   - Year
   - Area
   - Crime type
4. **Right-click** on any data point to access **drillthrough pages** for deeper insights.


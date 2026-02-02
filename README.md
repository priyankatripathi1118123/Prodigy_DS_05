# Prodigy Infotech – Data Science Internship  
## Task 05: Traffic Accident Data Analysis & Visualization  

---

## 📌 Objective
The objective of this task is to analyze and visualize **traffic accident data** to identify:
- Time-based accident patterns  
- Weather and severity relationships  
- Day vs night accident trends  
- Geographical accident hotspots  
- State-wise accident distribution  

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data loading and preprocessing  
- **NumPy** – numerical operations  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical and advanced plots  

---

## 📊 Dataset Information
- **Dataset Name:** US Accidents Dataset (Small Version)  
- **File Used:** `US_Accidents_Small.csv`  
- **Description:**  
  Contains accident records with details such as:
  - Start time and location  
  - Weather conditions  
  - Accident severity  
  - Visibility and precipitation  
  - State and day/night indicator  

---

## 🧹 Data Preprocessing
- Converted `Start_Time` to datetime format  
- Extracted **hour of the day** from accident start time  
- Verified dataset structure before visualization  

---

## 📈 Exploratory Analysis & Visualizations

### 1️⃣ Accidents by Hour of Day
- Histogram showing accident frequency for each hour  
- Helps identify peak accident hours  

### 2️⃣ Accidents by Weather Condition
- Count plot displaying accidents under different weather conditions  

### 3️⃣ Severity vs Weather Condition
- Visualizes how accident severity varies with weather  

### 4️⃣ Day vs Night Accidents
- Compares accidents occurring during day and night  

### 5️⃣ Visibility Distribution
- Histogram showing visibility levels during accidents  

### 6️⃣ Precipitation Distribution
- Displays precipitation values at the time of accidents  

### 7️⃣ Accident Hotspots
- KDE plot highlighting high-density accident locations  

### 8️⃣ Accidents by State
- Bar chart showing number of accidents per state  

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-link>

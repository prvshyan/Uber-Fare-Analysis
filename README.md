# 🚖 **Uber Fare Analysis Project**

## 📋 **Project Overview**
This project is a comprehensive **Exploratory Data Analysis (EDA)** of the Uber fare dataset. The goal of this analysis is to clean, explore, and visualize the data to uncover meaningful insights about Uber trips, including fare amounts, peak hours, and passenger counts.

The project is a part of my **Data Analysis Portfolio** to showcase my skills in data cleaning, visualization, and dashboard creation.

---

## 🧰 **Tools and Libraries Used**
- **Python**: For data cleaning and analysis.
- **Pandas**: To handle and manipulate the dataset.
- **NumPy**: For numerical operations.
- **Matplotlib**: For basic visualizations.
- **Seaborn**: For advanced visualizations.
- **Tableau**: For dashboard creation.

---

## 🗄️ **Dataset Description**
The dataset contains information about Uber trips, including:
- **fare_amount**: The cost of each trip in USD.
- **pickup_datetime**: The date and time when the trip started.
- **pickup_longitude** and **pickup_latitude**: The coordinates where the trip began.
- **dropoff_longitude** and **dropoff_latitude**: The coordinates where the trip ended.
- **passenger_count**: The number of passengers in the vehicle.

---

## 🧹 **Data Cleaning Process**
The following steps were taken to clean the dataset:
1. **Removed missing values**
2. **Converted `pickup_datetime` to datetime format**
3. **Removed invalid `fare_amount` values (e.g., negative fares)**
4. **Filtered out unrealistic `passenger_count` values (e.g., zero or more than 10 passengers)**

---

## 📊 **Exploratory Data Analysis (EDA)**
Key insights from the analysis:

### 1️⃣ **Fare Amount Distribution**
- Most trips have fares below **$50**.
- There are some **outliers** with fares above **$100**.

### 2️⃣ **Peak Hours Analysis**
- The **busiest hours** are between **5 PM and 8 PM**, indicating high demand during evening hours.
- There is also a noticeable spike in trips during **morning rush hours (7 AM to 9 AM)**.

---

## 📈 **Visualizations**
The following visualizations were created:
1. **Histogram**: Distribution of fare amounts.
2. **Box Plot**: To detect outliers in fare amounts.
3. **Bar Chart**: Number of trips per hour.
4. **Line Chart**: Number of trips per hour.
5. **Heatmap (in Tableau)**: Visualization of pickup locations.

---

## 🖥️ **Tableau Dashboard**
A **Tableau dashboard** was created to provide an interactive visualization of the analysis.

📌 **Link to Tableau Dashboard:** https://public.tableau.com/app/profile/shayan.alambeigi/viz/UberAnalysis_17368626837840/UberAnalysisDashboard

---

## 🧪 **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/prvshyan/Uber-Fare-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook Uber_EDA_Project.ipynb
   ```

---

## 📧 **Contact**
If you have any questions or feedback, feel free to reach out to me:
- **Email**: alambeigis6@gmail.com
- **LinkedIn**: linkedin.com/in/shayan-alambeigi
- **GitHub**: github.com/prvshyan

---

### 🔖 **Credits**
Dataset from: [Kaggle - Uber Fares Dataset](https://www.kaggle.com/yasserh/uber-fares-dataset)


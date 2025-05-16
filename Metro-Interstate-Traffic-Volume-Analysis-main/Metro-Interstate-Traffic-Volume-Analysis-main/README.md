# 🚗 Metro Interstate Traffic Volume Analysis

This project explores and analyzes traffic volume data collected from Interstate 94 (I-94) in Minneapolis-St Paul, Minnesota, to uncover patterns and relationships between traffic flow, time features, and weather conditions.

---

## 📊 Project Overview

The goal of this project is to study how traffic volume varies by hour, day, season, and weather. The insights are useful for urban planning, traffic management, and even as a baseline for predictive modeling.

---

## 📁 Dataset

- **Source**: [Kaggle - Metro Interstate Traffic Volume](https://www.kaggle.com/datasets/rgupta12/metro-interstate-traffic-volume)
- **Records**: ~48,000
- **Date Range**: 2012 - 2018  
- **Key Features**:
  - `date_time`: Timestamp of traffic count
  - `traffic_volume`: Number of cars recorded
  - `temp`: Temperature in Kelvin
  - `rain_1h`, `snow_1h`, `clouds_all`: Weather measures
  - `weather_main`, `weather_description`: Weather status categories

---

## 🧠 Objectives

- Analyze hourly, daily, and monthly traffic patterns.
- Understand the effect of weather conditions on traffic volume.
- Visualize trends to identify rush hours and low-traffic windows.
- Establish a foundation for future traffic prediction projects.

---

## 💻 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📌 Project Structure

metro-traffic-analysis/ ├── data/ │ └── Metro_Interstate_Traffic_Volume.csv ├── notebooks/ │ └── 01_traffic_eda.ipynb ├── output/ │ └── (for saving plots or reports) ├── README.md └── requirements.txt

---

## 🚦 Key Analysis Steps

- Data loading and cleaning.
- Feature engineering (hour, day, month, season extraction).
- Visual exploration using boxplots and correlation heatmaps.
- Weather condition impact assessment.
- Identification of peak traffic times.

---

## 📈 Sample Visualizations

- Traffic Volume by Hour of Day.
- Traffic Volume by Day of Week.
- Weather Impact Heatmap.

---

## 💡 Insights (Example)

- Peak traffic hours occur between **7-9 AM** and **4-6 PM**.
- **Weekdays** show much higher traffic volume compared to weekends.
- **Rain, snow, and temperature** have visible but moderate effects on traffic volume.

---

## 📥 How to Run

1. Clone this repository.
2. Open `notebooks/01_traffic_eda.ipynb` in Jupyter or Google Colab.
3. Upload the dataset to the `/data/` folder.
4. Run the cells sequentially to reproduce the analysis.

---

## 🚧 Future Work

- Build a **traffic volume prediction model**.
- Create an interactive **dashboard** for live traffic analysis.
- Integrate additional datasets like **events** or **holidays** for deeper insights.

---

## 🤝 Contributions

Pull requests and suggestions are welcome!  
If you want to extend this project, feel free to fork the repo or open an issue.


---


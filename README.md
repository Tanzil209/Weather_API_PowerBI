# 🌦️ Weather Dashboard (Power BI)

## 📌 Overview
This project is a **Power BI Dashboard** built using data from the [WeatherAPI](https://www.weatherapi.com/).  
It provides a **7-day weather forecast** along with key metrics such as:

- Current temperature and weather conditions  
- Humidity, wind speed, pressure, and visibility  
- Sunrise and sunset timings  
- Air Quality Index (AQI) with pollutant breakdown  
- Chance of rain for the coming week  

The dashboard gives a clean, interactive, and visual way to monitor weather trends.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **WeatherAPI** (REST API for weather data)  
- **Data Source**: JSON data pulled from WeatherAPI  
- **Languages Used**: M Query (for transformations), DAX (for measures)

---

## 📂 Repository Structure
```

my-powerbi-weather-dashboard/
│── weather-dashboard.pbix   # Power BI report file
│── sample\_data.json         # Example API response (for reference)
│── README.md                # Project documentation

````

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/my-powerbi-weather-dashboard.git
````

2. Open `weather-dashboard.pbix` in **Power BI Desktop**.
3. Replace the API key in the data source with your own [WeatherAPI key](https://www.weatherapi.com/my/).
4. Refresh the data to load the latest forecast.

---

## 🔑 Getting Your WeatherAPI Key

1. Sign up at [WeatherAPI](https://www.weatherapi.com/).
2. Get your **free API key** from your dashboard.
3. Replace it in Power BI’s query editor connection.

---

## 📊 Dashboard Preview

![Dashboard Screenshot](./screenshot.png)

<img width="2008" height="1123" alt="image" src="https://github.com/user-attachments/assets/f3b84ca2-9472-4e4b-886c-7db2e9117fdb" />

---

## 📌 Future Enhancements

* Add more cities dynamically through slicers.
* Integrate historical weather data.
* Deploy report to **Power BI Service** with scheduled refresh.

---

## 👨‍💻 Author

**Tanzil**



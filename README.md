# Weather Data Automation

An automated ETL pipeline that fetches real-time weather data from the OpenWeatherMap API, processes it using Python (Pandas), and stores it as a CSV file for analysis or further integration.

---

## Features
- Fetch real-time weather data for multiple cities.
- Secure API key handling using `.env`.
- ETL Pipeline: Extract → Transform → Load.
- Output stored in CSV format for easy use in analysis or visualization tools.

---

## Tools & Technologies Used
- Python → Core programming language.
- Requests → API calls.
- Pandas → Data transformation.
- python-dotenv → Secure environment variable management.
- OpenWeatherMap API → Weather data source.

---

## Project Architecture
<img width="500" height="450" alt="data_pipeline_architecture png" src="https://github.com/user-attachments/assets/e6297f3f-2573-41c9-9641-49f6bf4ef9e2" />


---

## Steps to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/weather-data-automation.git
cd weather-data-automation

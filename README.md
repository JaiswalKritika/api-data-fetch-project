# 📡 Real-Time API Data Ingestion & Processing Pipeline

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-150458.svg?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![REST API](https://img.shields.io/badge/REST-API_Integration-0055DA.svg?style=flat)](https://restfulapi.net/)

A Python-based data ingestion utility designed to fetch, parse, normalize, and process real-time data from external **RESTful APIs** using the `requests` library and `pandas`.

---

## 🌟 Key Features

- **RESTful API Integration**: Connects to HTTP endpoints with custom headers, query parameters, and authentication tokens.
- **JSON Data Normalization**: Converts complex, nested JSON responses into clean tabular DataFrames.
- **Error & Exception Handling**: Built-in HTTP status checking, request timeout handling, and retry logic.
- **Data Transformation**: Clean missing values, format timestamps, and aggregate key numerical fields.
- **Export Options**: Automatically saves cleaned data to CSV and JSON formats for analytics and reporting.

---

## 🛠️ Tech Stack

- **Core Language**: Python 3.10+
- **HTTP Requests**: Requests (`requests`)
- **Data Wrangling**: Pandas (`pandas`), NumPy (`numpy`)

---

## 🚀 Quickstart & Usage

```bash
# 1. Clone repository
git clone https://github.com/JaiswalKritika/api-data-fetch-project.git
cd api-data-fetch-project

# 2. Install dependencies
pip install -r requirements.txt

# 3. Execute data fetch pipeline
python fetch_data.py
```

---

## 📂 Project Structure

```
api-data-fetch-project/
├── fetch_data.py        # Main API fetching script
├── data/                # Exported CSV/JSON datasets
├── requirements.txt     # Python dependencies
└── README.md            # Documentation
```

---

## 👤 Author

**Kritika Jaiswal**  
- GitHub: [@JaiswalKritika](https://github.com/JaiswalKritika)  
- LinkedIn: [Kritika Jaiswal](https://www.linkedin.com/in/kritika-jaiswal205)

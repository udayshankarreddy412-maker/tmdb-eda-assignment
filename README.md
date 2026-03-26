# 🎬 TMDB Movie Data Pipeline with Python

## 📌 Project Overview

This project demonstrates a simple data pipeline built using the TMDB (The Movie Database) API. The pipeline extracts movie data, transforms it into a structured format using pandas, and stores it in a SQLite database for further analysis.

The goal of this project is to showcase practical skills in API handling, data processing, and database integration using Python.

---

## ⚙️ Tech Stack

* Python
* Requests (API calls)
* Pandas (data manipulation)
* SQLite (data storage)

---

## 🚀 Features

* Fetches movie data from TMDB Discover Movies API
* Extracts relevant fields such as title, release date, popularity, and ratings
* Converts raw JSON data into a structured pandas DataFrame
* Stores processed data into a SQLite database (`movies.db`)
* Handles multiple pages to collect more than 20 movies

---

## 📂 Project Structure

```
├── main.py          # Main pipeline script
├── movies.db        # SQLite database (generated after running script)
├── README.md        # Project documentation
```

---

## 🔄 Data Pipeline Steps

1. **Extract**
   Fetch movie data from TMDB API using HTTP requests.

2. **Transform**
   Clean and structure the JSON response into a pandas DataFrame.

3. **Load**
   Store the transformed data into a SQLite database table named `movies`.

---

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the project folder:

```
cd your-repo-name
```

3. Install dependencies:

```
pip install requests pandas
```

4. Add your TMDB API key in the script:

```python
API_KEY = "your_api_key_here"
```

5. Run the script:

```
python main.py
```

---

## 📊 Output

* A SQLite database file (`movies.db`)
* Table: `movies`
* Contains structured movie data ready for analysis

---

## ⚠️ Limitations

* No automated scheduling (manual execution required)
* Basic error handling
* API key is stored locally (not secured via environment variables)

---

## 🔮 Future Improvements

* Add logging and exception handling
* Use environment variables for API key security
* Automate pipeline using scheduling tools (e.g., cron or Airflow)
* Extend analysis with visualizations

---

## 👤 Author

Uday Shankar Reddy

---

## 📄 License

This project is for educational purposes only.

# spotipy-pipeline
# 🎧 Spotify Track Insights – Data Pipeline & Visualization Project

This project started with a simple goal: explore music data from Spotify.  
It quickly evolved into a mini end-to-end **data engineering + analytics pipeline** powered by real-time API data, SQL, Docker, and interactive dashboards.

---

## 📌 Project Overview

### ✅ What I Did

1. **Fetched real-time track metadata** using the [Spotify for Developers API](https://developer.spotify.com/documentation/web-api/)
2. **Stored data in a local MySQL database** using Python + `mysql-connector`
3. **Visualized insights** in the browser using [Metabase](https://www.metabase.com/) running inside Docker

### 🛠 Tech Stack

- **Python** for API calls and data handling
- **MySQL** (local) for structured storage
- **Metabase + Docker** for clean dashboards
- **Jupyter Notebook** for exploration + testing

---


### Run Metabase (browser-based dashboard):
```bash
docker run -d -p 3000:3000 --name metabase metabase/metabase

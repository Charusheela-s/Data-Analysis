# 🇩🇪 German Long-Distance Public Transport Analysis (GTFS + SQL)

This project explores long-distance rail transport in Germany using the official GTFS dataset and PostgreSQL hosted on [Railway.app](https://railway.app). It focuses on analyzing operational patterns, busiest stations, travel durations, and more.

## 📦 Dataset

- **Source:** [GTFS.de – Long Distance Rail Feed](https://gtfs.de/en/)
- **Format:** GTFS (General Transit Feed Specification)
- **Files Used:**
  - `agency.txt`
  - `routes.txt`
  - `trips.txt`
  - `stop_times.txt`
  - `stops.txt`
  - `calendar.txt`
  - `calendar_dates.txt`

## 🛠️ Tech Stack

| Tool            | Purpose                     |
|-----------------|-----------------------------|
| PostgreSQL      | Database for GTFS data      |
| Railway.app     | Cloud hosting for PostgreSQL|
| SQL             | Data analysis and querying  |
| DBeaver         | GUI for table import/query  |
| GitHub          | Code and analysis versioning|

---

## 🏗️ Schema Overview

- **routes**: route metadata (ID, operator, type)
- **trips**: actual scheduled trips
- **stop_times**: each stop along a trip with times
- **stops**: all stations with coordinates
- **calendar / calendar_dates**: schedule validity



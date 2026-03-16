# ev-charging-recommendation
Route-based EV charging recommendation system with real-time traffic data
# EV Charging Station Placement & Recommendation System

> A route-based EV charging recommendation system using real-time traffic and geographic data — reducing travel time by 20–30%.

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Tools](https://img.shields.io/badge/Tools-Python%20%7C%20Geospatial%20%7C%20Optimization-3776AB)

---

## 📌 Project Overview

As EV adoption accelerates, finding optimal charging stations en route is a critical pain point for drivers. This project builds a recommendation system that factors in real-time traffic conditions, geographic location, and battery constraints to suggest the most efficient charging stops along a given route.

---

## 🎯 Objectives

- Build a **route-based EV charging recommendation system** using real-time data
- Minimize **battery consumption** and **travel time** through optimized routing logic
- Reduce overall route travel time by recommending strategically placed charging stops
- Provide a scalable framework adaptable to different EV ranges and routes

---

## ⚙️ How It Works

1. **Input** — User provides start point, destination, and current battery level
2. **Route Fetching** — Real-time traffic and road data fetched along the route
3. **Station Filtering** — Charging stations filtered by proximity and compatibility
4. **Optimization** — Routing logic minimizes total travel time + charging stops
5. **Output** — Recommended charging stations with estimated stops and time savings

---

## 📊 Results

- Improved route efficiency with **20–30% reduction in travel time**
- Optimization logic consistently minimized unnecessary detours to charging stations
- System adapts dynamically based on real-time traffic conditions

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Geospatial | Geographic data APIs, coordinate mapping |
| Optimization | Route optimization algorithms |
| Data | Real-time traffic data, EV station datasets |

---

## 📁 Repository Structure

```
ev-charging-recommendation/
├── data/
│   ├── charging_stations.csv         # Charging station dataset
│   └── sample_routes.json            # Sample route inputs
├── src/
│   ├── route_fetcher.py              # Traffic & route data
│   ├── station_filter.py             # Station compatibility logic
│   ├── optimizer.py                  # Core routing optimizer
│   └── recommender.py                # Main recommendation engine
├── notebooks/
│   └── ev_recommendation_demo.ipynb  # End-to-end demo
├── outputs/
│   └── sample_recommendation.json
└── README.md
```

---

## 🔮 Future Improvements

- [ ] Integrate real-time EV station availability APIs
- [ ] Add multi-stop trip planning support
- [ ] Build an interactive map visualization layer
- [ ] Extend to support multiple EV models with different range profiles

---

## 👩‍💻 Author

**Vaishnavi Perka** — [LinkedIn](https://www.linkedin.com/in/vaishnavi-perka) · [Portfolio](https://vaishnaviperka.github.io)

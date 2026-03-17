# ChargeWise: Smart Navigation & EV Charging Station Recommendation

> A web application that helps electric vehicle drivers locate nearby charging stations, find optimal routes, and monitor real-time traffic — powered by TomTom APIs and GIS.

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Type](https://img.shields.io/badge/Type-B.Tech%20Major%20Project-blue)
![Tech](https://img.shields.io/badge/Tech-TomTom%20API%20%7C%20GIS%20%7C%20HTML%2FCSS%2FJS-orange)
![University](https://img.shields.io/badge/University-RGUKT%20Basar-green)

---

## 📌 Project Overview

**ChargeWise** addresses one of the key barriers to EV adoption — range anxiety and limited charging infrastructure accessibility. The system enables EV drivers to locate nearby charging stations, plan optimized routes considering real-time traffic, and visualize live traffic conditions, all through an interactive web interface.

This project was developed as a B.Tech Major Project at **Rajiv Gandhi University of Knowledge Technologies (RGUKT), Basar** under the guidance of **Mrs. P. Sarika Rao**, Assistant Professor, Dept. of CSE.

> **Team:** Perka Vaishnavi (B182287) · Kasarla Vyshnavi Priya (B181864) · Nutakki Lochani Lakshmi (B181875)

---

## 🎯 Objectives

- Efficiently locate nearby EV charging stations based on user-defined location and radius
- Optimize route planning considering distance, real-time traffic, and charging station availability
- Analyze real-time traffic patterns using TomTom Traffic API
- Reduce travel time and energy consumption for EV drivers
- Provide a scalable, user-centric web interface for global use

---

## ✨ Key Features

### 1. Nearby Charging Station Locator
- User inputs a location name and search radius
- App geocodes the location using the TomTom Search API
- Fetches nearby EV charging stations (POIs) within the specified range
- Displays results on an interactive map with markers showing address, plug types, power ratings, and availability

### 2. Optimal Route Planner
- User enters a starting location and destination
- App uses TomTom Routing API to calculate the most efficient path
- Incorporates real-time traffic data to minimize travel time and avoid congestion
- Displays route visually on an interactive map with turn-by-turn waypoints

### 3. Real-Time Traffic Detector
- Fetches live traffic data from the TomTom Traffic API
- Displays traffic incidents (accidents, road closures, construction) as map markers
- Color-coded overlays show congestion levels: light, moderate, and heavy
- Bounding box visualization highlights the extent of traffic disruptions

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Mapping & Navigation | TomTom Maps API, TomTom Routing API |
| Traffic Data | TomTom Traffic API |
| Location Search | TomTom Search API (Geocoding, POI Search) |
| Geospatial Analysis | Geographic Information System (GIS) |

---

## ⚙️ How It Works

```
User Input (location + radius)
        ↓
TomTom Search API → Geocoding → Coordinates
        ↓
POI Search → Nearby EV Charging Stations
        ↓
Map Interface → Interactive Markers + Station Details
```

```
User Input (start + destination)
        ↓
TomTom Maps API → Geocoding
        ↓
TomTom Routing API → Optimal Route (real-time traffic aware)
        ↓
Map Interface → Route Visualization + Navigation Instructions
```

---

## 📁 Repository Structure

```
ev-charging-recommendation/
├── index.html          # Homepage — About, Stations, Ports, Services, Contact
├── ev_search.html      # Nearby charging station search (TomTom Search API)
├── ev_routing.html     # Route finder — start to destination (TomTom Routing API)
├── traffic.html        # Real-time traffic detector (TomTom Traffic API)
├── images/
│   ├── logo1.png
│   ├── bg.jpg
│   ├── about.gif
│   ├── first.jpg
│   ├── Stations available.png
│   ├── circle1.jpg
│   ├── route1.jpg
│   └── circle3.jpg
├── Final_report_btech_project.docx   # Full B.Tech project report
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/VaishnaviPerka/ev-charging-recommendation.git
cd ev-charging-recommendation
```

2. Get a free TomTom API key at: https://developer.tomtom.com

3. Add your API key in `ev_search.html`, `ev_routing.html`, and `traffic.html`:
```javascript
const API_KEY = 'your_tomtom_api_key_here';
```

4. Open `index.html` in your browser — no server setup needed.

> The app navigates across 4 pages: Homepage → Search Stations → Find Route → Traffic Detector

---

## 📊 Results

- Successfully locates EV charging stations globally using real-time POI data
- Route optimization reduces travel time by **20–30%** by avoiding congested routes
- Traffic detector provides live incident and congestion visualization across regions
- User-centric design tested across diverse urban environments

---

## 🔮 Future Improvements

- [ ] Integrate renewable energy source data (solar-powered stations)
- [ ] Add battery range estimator based on route distance and traffic
- [ ] Mobile app version (React Native or Flutter)
- [ ] Incorporate vehicle-to-grid (V2G) smart charging scheduling
- [ ] Multi-stop route planning with automatic charging stop insertion

---

## 📜 References

- Chen, Y., Cheng, C., & Huang, T. — *EV Routing and Charging Optimization*
- Bhalla, S. — *Cutting-Edge Electric Vehicle Route Planner Technology*
- Liu, Y., & Zhang, H. — *Real-time Traffic Incident Detection using Machine Learning*
- TomTom Developer Documentation: https://developer.tomtom.com/docs

---

## 👩‍💻 Authors

**Vaishnavi Perka** — [LinkedIn](https://www.linkedin.com/in/vaishnavi-perka) · [Portfolio](https://vaishnaviperka.github.io)  
Kasarla Vyshnavi Priya · Nutakki Lochani Lakshmi  
*B.Tech CSE, RGUKT Basar — Under guidance of Mrs. P. Sarika Rao*

# 🇯🇵 Japan Data Visualization Project

## 📌 Overview

This project provides an interactive web-based visualization of three key datasets related to Japan:

- **Japanese Universities**
- **Earthquake Incidents (2001–2018)**
- **High-rise Tower Apartments**

Users can explore geographical distributions, visualize correlations, and analyze regional patterns through a combination of bar charts, scatter plots, and a dynamic map interface.

---

---

## 📊 Features

### ✅ Bar Charts (`bar_charts.html`)
- Visualizes the number of universities, earthquakes, and tower apartments per region.
- Also includes comparison charts across regions between:
  - Universities vs. Earthquakes
  - Universities vs. Apartments
  - Earthquakes vs. Apartments

### ✅ Scatter Plots (`scatter_plots.html`)
- Geographical scatter plots for each dataset based on latitude and longitude.
- Displays trend lines using simple-statistics.js to indicate correlation.
- Interactive tooltips with metadata (e.g., earthquake magnitude, university names).

### ✅ Map View (`map.html`)
- Built using Leaflet and MarkerCluster.
- Shows clusters of:
  - University locations
  - Earthquake epicenters
  - Apartment buildings
- Color-coded markers and cluster icons.
- Tooltips display relevant details upon clicking.

### ✅ Homepage (`index.html`)
- Stylish full-page layout with:
  - Background image
  - Navigation buttons for charts and maps
  - Animated GIF for visual appeal

---

## 🛠️ Libraries & Tools

- **Chart.js** – For bar and scatter plots
- **Leaflet.js** – For interactive maps
- **PapaParse.js** – To load and parse CSV data
- **Simple-Statistics.js** – To calculate trend lines and correlations
- **Leaflet MarkerCluster** – Efficient marker clustering on the map

---

## 📦 Setup Instructions

1. Clone or download the project folder.
2. Ensure all necessary CSV, JSON, and image files are in the same directory.
3. Open `index.html` in your browser to start exploring.

> 💡 No server setup is needed. All scripts run client-side.

---

## 📌 Notes

- Ensure internet access is available as external libraries are loaded via CDN.
- Data preprocessing (region classification, regression lines) is handled dynamically in the browser.

---

## 📃 License

This project is for educational and visualization purposes. Attribution is appreciated if reused or modified.

---

## 🙌 Acknowledgements

- OpenStreetMap contributors
- Chart.js and Leaflet.js developers
- Japanese data sources (public domain datasets)




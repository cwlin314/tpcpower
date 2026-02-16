# TPC Power Dashboard - Integrated Monitoring System

![Project Preview](preview_mockup.png)

> **Real-time Monitoring, Trend Analysis, All-in-One Dashboard.**
> This project is a high-end power monitoring dashboard built with traditional web technologies, designed to provide real-time visualization of Taiwan's electricity generation data.

## 🚀 Key Features

- **Real-time KPI Tracking**: Monitor total power generation, system load factor, total green energy, and Renewable Energy ratio (RE%).
- **Dynamic Energy Mix**: A center-carousel doughnut chart that automatically cycles through core metrics with detailed energy proportion analysis.
- **National GIS Map**: Integrated Leaflet map displaying the geographic distribution of power plants with dynamic pulse effects, real-time output, and load status.
- **Instant Data Table**: A searchable, detailed list covering all generating units (including Nuclear, Coal, Gas, Hydro, Wind, Solar, etc.).
- **Auto-Sync Mechanism**: Built-in 10-minute timer for automatic synchronization with Taipower Open Data, ensuring zero-latency updates.

## 🛠️ Tech Stack

- **Core Layout**: HTML5, [Tailwind CSS](https://tailwindcss.com/)
- **Dynamic Charts**: [Chart.js](https://www.chartjs.org/)
- **Geospatial Visualization**: [Leaflet.js](https://leafletjs.org/)
- **Iconography**: [Lucide Icons](https://lucide.dev/)
- **Development**: Vanilla JavaScript (ES6+), Open Data API Integration

## 📜 Data Source & Documentation

Data is sourced from **Taiwan Power Company (Taipower)** official Open Data:
- **API (JSON)**: `https://service.taipower.com.tw/data/opendata/apply/file/d006001/001.json`

The system includes a multi-proxy loading mechanism (AllOrigins, CorsProxy, CodeTabs, etc.) to ensure reliable data fetching despite cross-origin (CORS) restrictions.

## 📦 Quick Start

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser.
3. The dashboard auto-refreshes every 10 minutes. You can also click "Sync Data" in the top-right corner to manual update.

---

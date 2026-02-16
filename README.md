# ⚡ TPC Power Dashboard
## Taiwan Electricity System — Real-Time Open Energy Visualization

<p align="center">
Real-time visualization platform for Taiwan’s national electricity generation system powered by open data.
</p>

<p align="center">

![Status](https://img.shields.io/badge/status-active-success)
![Open Data](https://img.shields.io/badge/data-open--energy-blue)
![Frontend](https://img.shields.io/badge/frontend-vanilla%20web-lightgrey)
![License](https://img.shields.io/badge/license-MIT-green)
![Made in Taiwan](https://img.shields.io/badge/made%20in-Taiwan-red)

</p>

---

## 🌍 About the Project

**TPC Power Dashboard** is an open energy visualization project that transforms Taiwan Power Company’s public datasets into a real-time operational dashboard.

The platform provides an accessible view of Taiwan’s electricity system, enabling users to understand:

- National power generation status
- Renewable energy penetration
- Plant-level operational transparency
- Geographic distribution of power assets

All computation and visualization run entirely inside the browser, demonstrating how open infrastructure data can be transformed into actionable insights using lightweight web technologies.

---

## 🖥 Live Demo

👉 https://twtpcpower.netlify.app/

---

## ✨ Core Features

### ⚡ Real-Time Grid Monitoring

Monitor Taiwan’s electricity system instantly:

- Total generation output
- System load factor
- Renewable generation
- Renewable Energy Ratio (RE%)

Data automatically updates every **10 minutes**.

---

### 📊 Energy Mix Visualization

Interactive dynamic charts visualize Taiwan’s real-time energy structure, enabling intuitive understanding of grid composition and energy transition progress.

---

### 🗺 National Power Plant GIS Map

Interactive geographic visualization powered by Leaflet:

- Nationwide power plant locations
- Real-time generation indicators
- Operational activity visualization
- Spatial awareness of grid infrastructure

---

### 🔎 Unit-Level Transparency

Searchable detailed dataset including:

- Nuclear
- Coal
- Natural Gas (LNG)
- Hydro
- Wind
- Solar
- Cogeneration units

Designed for researchers, analysts, educators, and energy enthusiasts.

---

### 🔄 Automatic Data Synchronization

Built-in resilient data loading system:

- Auto refresh every **10 minutes**
- Manual synchronization supported
- Multi-proxy fallback mechanism
- CORS handling and retry logic

Ensures stable global accessibility.

---

## 🧠 System Architecture

```
          Taipower Open Data API
                     │
                     ▼
           Proxy Failover Layer
     (AllOrigins / CORS Proxy / Fallback)
                     │
                     ▼
            Data Processing Engine
               Vanilla JavaScript
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼
   Chart.js       Leaflet Map     Data Table
 Visualization     GIS Engine     UI Layer
                     │
                     ▼
              Browser Dashboard
```

---

## 🛠 Technology Stack

| Category | Technology |
|---|---|
| UI | HTML5 |
| Styling | Tailwind CSS |
| Visualization | Chart.js |
| Mapping | Leaflet.js |
| Icons | Lucide Icons |
| Logic | Vanilla JavaScript (ES6+) |
| Deployment | Netlify |
| Data Source | Taipower Open Data |

**Design Philosophy**

- Zero backend dependency  
- Lightweight architecture  
- Open data accessibility  
- Visual-first analytics  

---

## 📡 Data Source

Official open dataset provided by **Taiwan Power Company (Taipower)**:

```
https://service.taipower.com.tw/data/opendata/apply/file/d006001/001.json
```

This project demonstrates practical reuse of governmental open energy datasets for education, transparency, and research purposes.

---

## 🚀 Quick Start

Clone the repository:

```bash
git clone https://github.com/cwlin314/tpcpower.git
cd tpcpower
```

Open directly:

```
index.html
```

✅ No installation required  
✅ No build tools required  
✅ Works in any modern browser  

---

## 🎯 Use Cases

- Energy system education
- Open data visualization
- Policy communication
- Grid monitoring dashboards
- Research demonstrations
- Energy transition awareness

---

## 🌱 Roadmap

- [ ] Historical generation analytics
- [ ] Carbon intensity estimation
- [ ] Demand forecasting visualization
- [ ] Mobile-first responsive UI
- [ ] Dark mode command center
- [ ] AI-powered energy insights
- [ ] API abstraction layer

---

## 🤝 Contributing

Contributions and ideas are welcome.

Suggested contribution areas:

- Energy analytics
- Visualization enhancement
- Performance optimization
- Additional open energy datasets

Steps:

1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request

---

## 🌏 Related Open Energy Projects

Inspired by global open-energy initiatives:

- electricityMap
- energy-charts.info
- Open Power System Data
- Ember Climate dashboards

---

## 📄 License

MIT License

---

## ⭐ Support

If this project helps improve understanding of energy systems:

Give the repository a ⭐ and share it with the open energy community.

---

## 💡 Preview

<img width="2671" height="4855" alt="tpc" src="https://github.com/user-attachments/assets/0e50a8a7-81d7-4146-b623-9889206a2bd3" />

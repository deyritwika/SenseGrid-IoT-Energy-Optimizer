# SenseGrid – Smart Home Energy Intelligence Prototype



## 📌 Overview
SenseGrid is a hands-on IoT project that simulates how smart homes can monitor and optimize energy usage.  
This prototype blends **real device integration** (smart bulb), **simulated data**, and **product management rigor** (PRD, roadmap, KPIs) to create a realistic, portfolio-ready IoT product case study.

## ✨ Key Features
- **Real Device Discovery:** Detect devices on the local network (e.g., smart bulb).
- **Energy Monitoring:** Simulate and track per-device energy consumption.
- **Anomaly Detection:** Identify potential energy waste (e.g., devices left ON for long periods).
- **Cost Estimation:** Estimate power costs based on simulated consumption.
- **Interactive Dashboard:** Built with Python Dash for real-time visualization.
- **Scalable Roadmap:** Designed for multi-device orchestration and AI-driven optimization.

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries:** Dash, Plotly, Pandas, paho-mqtt
- **IoT Protocols:** MQTT (simulated or real integration)
- **Devices:** Smart bulb, Google Home (for discovery context)


## 🚀 Getting Started

### 1. Clone the Repository
````bash
git clone https://github.com/deyritwika/sensegrid-iot-energy-optimizer.git
cd sensegrid-iot-energy-optimizer
````
### 2. Install Dependencies
````bash
pip install -r src/requirements.txt
````
### 3. Run the Dashboard
````bash
python src/dashboard.py
````
### 4. View in Browser
Open your browser at:

```
http://127.0.0.1:8050/
```

### 📊 Architecture

(Devices → MQTT/Simulation → Data Pipeline → Dashboard)
<img width="1536" height="1024" alt="Image Aug 4, 2025, 09_37_39 PM" src="https://github.com/user-attachments/assets/b851007c-f044-4c8b-9c85-d9507e4aec4c" />



### 📅 Roadmap
Phase 1: Single device monitoring (MVP)

Phase 2: Multi-device orchestration and cloud integration (AWS IoT, Azure IoT)

Phase 3: AI-powered optimization engine

### 🧪 Example Use Cases
Monitor smart bulb usage and detect anomalies

Simulate energy costs and track trends

Create a proof-of-concept for scalable IoT energy solutions

### 📈 KPIs
Energy usage reduction potential (simulated %)

Real-time dashboard refresh rate

Accuracy of anomaly detection

### 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.





# SenseGrid – Product Requirements Document (PRD)

## 1. Overview
SenseGrid is a smart home energy intelligence platform prototype that enables real-time monitoring, anomaly detection, and cost estimation for connected devices. It blends hands-on IoT engineering with product strategy, serving as an MVP for a future energy-optimization platform.

## 2. Problem Statement
Homes are filled with connected devices, yet users lack visibility into energy consumption patterns and actionable insights to reduce waste.

## 3. Target Audience
- Tech-savvy homeowners
- Energy-conscious users
- IoT developers and enthusiasts

## 4. Goals
- Build a prototype to monitor device-level energy usage
- Provide an intuitive dashboard for visualization
- Implement basic anomaly detection for energy waste
- Lay the foundation for a scalable IoT energy product

## 5. Key Features
- Device discovery (real devices like smart bulbs)
- Energy consumption monitoring (simulated wattage)
- Anomaly alerts (e.g., device left ON for extended periods)
- Cost estimation
- Interactive dashboard

## 6. Success Metrics (KPIs)
- Simulated % of potential energy cost reduction
- Real-time dashboard refresh latency
- Accuracy of anomaly detection
- User interaction with dashboard (mocked)

## 7. Technical Overview
- Devices: Smart bulb, Google Home (for discovery context)
- Data Pipeline: Simulated + device status
- Protocol: MQTT or simulated ingestion
- Dashboard: Python Dash/Plotly
- Deployment: Local environment

## 8. Roadmap (High-Level)
- Phase 1: MVP with single-device monitoring
- Phase 2: Multi-device orchestration
- Phase 3: AI-driven optimization

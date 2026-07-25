# EcoLoop: AI-Powered Building Energy Optimization

## Project Overview

EcoLoop is an AI-powered smart building energy optimization system that combines a Large Language Model (LLM) with EnergyPlus building simulations to improve energy efficiency while maintaining occupant comfort.

The system monitors building parameters such as temperature, occupancy, humidity, and energy consumption. Based on these inputs, the AI recommends optimized HVAC settings to reduce electricity usage.


## Features

- AI-powered HVAC optimization
- Large Language Model (Qwen)
- Building energy simulation
- Energy consumption analysis
- Baseline vs Optimized Building Models
- CSV report generation
- Energy savings visualization


## Technologies Used

- Python
- Google Colab
- EnergyPlus
- Qwen LLM
- Pandas
- NumPy
- Matplotlib
- GitHub


## Project Structure

EcoLoop/
│
├── notebooks/
├── building_models/
│   ├── baseline_building.idf
│   └── optimized_building.idf
│
├── weather/
├── results/
├── dashboard/
├── README.md
└── requirements.txt


## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/EcoLoop.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook in Google Colab.

4. Mount Google Drive.

5. Run all notebook cells.

---

## Project Workflow

Building Model (.idf)
        ↓
EnergyPlus Simulation
        ↓
Sensor Data
        ↓
LLM Decision Engine
        ↓
Optimized HVAC Settings
        ↓
Energy Savings
## Results

The project demonstrates:

- Reduced energy consumption
- Intelligent HVAC control
- AI-driven optimization
- Improved sustainability

---

## Future Improvements

- Live IoT sensor integration
- Real-time dashboard
- Multi-building optimization
- Cloud deployment


Honeywell Project

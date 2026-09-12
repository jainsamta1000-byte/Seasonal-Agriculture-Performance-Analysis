# Seasonal Agriculture Performance Analysis

## Problem Statement
Agricultural performance varies across seasons due to environmental conditions,
farming practices, resource availability and market conditions. This project
analyzes a seasonal agriculture dataset to identify meaningful patterns, trends,
and relationships in crop performance across Kharif, Rabi and Zaid seasons.

## Dataset
- 4,000 farm records
- 8 states, 8 crops (Wheat, Rice, Maize, Cotton, Pulses, Groundnut, Chilli, Sugarcane)
- 3 seasons (Kharif, Rabi, Zaid)
- 28 attributes including yield, profit, rainfall, temperature, irrigation method,
  water efficiency, and disease/pest risk

## Technology Used
- Python 3
- Pandas & NumPy – data cleaning and aggregation
- Matplotlib & Seaborn – visualization
- Jupyter Notebook – analysis environment

## Key Findings
- Kharif is the top-performing season (5.64 t/Ha average yield)
- Zaid season runs at a loss on average (-₹25K/farm)
- Sugarcane, Chilli and Cotton are the most profitable crops
- Water-use efficiency is the strongest driver of yield (r = 0.92)
- Flood irrigation is the most common method (33%) despite lower efficiency
- Disease/pest risk peaks in Kharif season (54.5%)

## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open and run the notebook: `jupyter notebook analysis.ipynb`

## Future Scope
- Build ML models to predict yield and profit before the season starts
- Add real-time weather and market-price feeds
- Develop a farmer-facing dashboard/app for season-wise crop advisory
- Integrate satellite/remote-sensing data for soil and crop-health monitoring

## Author
[Your Name] | AICTE Student ID: [Your ID]

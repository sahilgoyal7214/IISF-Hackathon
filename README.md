# **Dynamic Temporal Analytics System – IISF Hackathon 2023**

## 📌 Overview  
This project was developed for the **IISF Hackathon 2023**, organized by **Hack2Skill** as part of the **India International Science Festival (IISF)**. Our solution, titled **Dynamic Temporal Analytics System**, addresses the challenge outlined in [Topic 13](https://bhuvan.nrsc.gov.in/hackathon/iisf2023/topics/Topic13.pdf):  
> *“Data Dynamics using DL/ML over a time scale – A cluster/trend analysis”*

The goal is to analyze time-sensitive data to uncover evolving patterns, trends, and anomalies that can drive real-time decision-making.

## 🎯 Problem Statement  
Develop a system that:
- **Analyzes temporal trends:** Discerns emerging patterns, clusters, and fluctuations over time.
- **Adapts dynamically:** Utilizes deep learning and machine learning models that adjust to changing temporal dynamics.
- **Provides actionable insights:** Enables proactive responses by identifying anomalies and forecasting future trends.

## 🚀 Key Features  
✅ **Time Series Forecasting:** Implements statistical (e.g., ARIMA) and deep learning (e.g., LSTM) models to predict future trends.  
✅ **Dynamic Trend Analysis:** Detects clusters and trends within temporal datasets such as temperature variations and sunspot activity.  
✅ **Interactive Visualizations:** Generates real-time dashboards to visualize emerging patterns and anomalies.  
✅ **Anomaly Detection:** Identifies deviations from expected temporal patterns to alert decision-makers promptly.

## 📂 Repository Structure  
The project repository is organized as follows:
```
/IISF-Hackathon
│── /models
│   ├── avg_temp_lstm_model.h5              # LSTM model for average temperature prediction
│   └── sunspots_lstm_model.h5              # LSTM model for forecasting sunspot activity
|── /notebook            
│   ├── ARIMA.ipynb                # ARIMA model implementation for univariate time series forecasting
│   ├── RNNs.ipynb                 # Recurrent Neural Networks for capturing temporal dependencies
│   ├── avg_temp_lstm.ipynb        # LSTM model for average temperature prediction
│   ├── hybrid_temp.ipynb          # Hybrid model combining statistical and DL methods for forecasting temperature trends
│   ├── minimum_temperature.ipynb  # Analysis of minimum temperature patterns
│   ├── sunspots_cnn.ipynb         # CNN-based model for sunspot activity prediction
│   └── sunspots_lstm.ipynb        # LSTM-based model for forecasting sunspot activity
│── /data
│   ├── minimum_temperature.csv    # Dataset for minimum temperature analysis
│   └── sunspots.csv               # Dataset for sunspot activity analysis
│── requirements.txt               # List of project dependencies
│── README.md                      # Project documentation
```

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/sahilgoyal7214/IISF-Hackathon.git
cd IISF-Hackathon
```

### 2️⃣ Install Dependencies  
Ensure you have **Python 3.8+** installed, then run:  
```bash
pip install -r requirements.txt
```

### 3️⃣ Explore the Notebooks  
Open and run the Jupyter notebooks in the `/notebook` directory using Jupyter Notebook or JupyterLab to:
- Conduct exploratory data analysis.
- Train and evaluate forecasting models.

## Model evaluation 
![Prediction Graph](https://github.com/sahilgoyal7214/IISF-Hackathon/blob/main/actual_vs_predicted.png?raw=true)

## 🏆 About IISF Hackathon 2023  
The **India International Science Festival (IISF) Hackathon 2023**, powered by **Hack2Skill**, is a prestigious event where innovators address scientific and technological challenges using AI and machine learning.  
🔗 **Learn More:** [IISF Hackathon 2023](https://hack2skill.com/hack/iisf-hackathon-2023)

## 👨‍💻 Contribution Guide  
If you’d like to contribute:
1. **Fork the repository.**

2. **Create a new branch:**  
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit your changes:**  
   ```bash
   git commit -m "Describe your changes"
   ```
4. **Push to your branch:**  
   ```bash
   git push origin feature-branch
   ```
5. **Submit a Pull Request.**


Feel free to modify or expand upon this documentation as your project evolves!
## Authors

- [Sahil Goyal](https://www.github.com/sahilgoyal7214)
- [Vaibhav Sharma](https://github.com/vaibhav7766)
- [Suyash Tambe](https://www.github.com/suyashtambe)
- [Shhreyash Pandey](https://www.github.com/ShhreyashPandey)


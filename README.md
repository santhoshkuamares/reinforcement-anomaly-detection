RL-for-Anomaly-Detection
Project Overview:

This project applies Reinforcement Learning (RL) to anomaly detection in industrial for machine overheat.
Using the AI4I 2020 Predictive Maintenance Dataset, the goal is to detect  machine over heat befoehand more effectively than traditional models like Isolation Forest.

Dataset

Source: UCI Machine Learning Repository – AI4I 2020 Dataset
Size: 10,000 rows, 14 columns
Target Variable: Machine Failure (binary: 0 = normal, 1 = failure)
Features Used:
Sensor readings (Air Temperature, Process Temperature, Torque, Rotational Speed, etc.)
Engineered features:
Temp_Diff = Process temperature – Air temperature
Power = Torque × Rotational Speed

How to Run?

1. Clone the repository: git clone https://github.com/<your-username>/RL-for-Anomaly-Detection.git
cd RL-for-Anomaly-Detection
2. Install dependencies: pip install -r requirements.txt
3. Run the notebook or script: python rl_anomaly_detection.py

Requirements:
1. Python 3.8+
2. pandas, numpy, matplotlib, seaborn
3. scikit-learn
4. PyTorch

References

Matzka, S. (2020). Explainable Artificial Intelligence for Predictive Maintenance Applications.
UCI ML Repository: AI4I 2020 Predictive Maintenance Dataset.

Contact:
saisanthosh7092@gmail.com

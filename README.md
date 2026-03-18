# Real-Time-Fraud-Detection-Pipeline-with-Python-Kafka-Machine-Learning
Real time fraud detection system using Python, FastAPI, and machine learning to simulate transaction risk scoring and decisioning (ALLOW/REVIEW/BLOCK).

## Features
- Rule based fraud detection engine
- Machine learning based risk scoring
- Real time API for transaction scoring
- Simulated fraud data generator

## Tech Stack
- Python
- FastAPI
- Scikit learn (future)
- Pandas (future)

## Architecture
Data → Rule Engine + ML Model → Risk Score → API Response

## Example Output
{
  "risk_score": 87,
  "decision": "BLOCK",
  "reasons": ["high_amount", "high_ip_risk"]
}

# 📱 Mobile Phone Pricing Prediction

A clean, reproducible project to predict smartphone price ranges using machine-learning.

## 🎯 Project Overview  
This repository uses hardware specs (RAM, camera, battery, screen size, etc.) to train a model that classifies mobile phones into four price categories:  
- 0 → Low  
- 1 → Medium  
- 2 → High  
- 3 → Very High  

## 📂 Files  
- `dataset.csv` — dataset of mobile phone features + `price_range` label  
- `Mobile Phone Pricing.ipynb` — notebook with EDA, preprocessing, modelling & evaluation  
- `Predict Mobile Phone Pricing.pdf` — problem statement and project brief  

## 🚀 Quick Start (macOS)  
```bash
git clone https://github.com/PardhivAryan/Mobile-Phone-Pricing.git  
cd Mobile-Phone-Pricing  
python3 -m venv .venv  
source .venv/bin/activate  
pip install -r requirements.txt  
jupyter notebook  


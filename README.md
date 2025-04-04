# Investment-Strategies  
Analysis of algorithmic investment strategies.

**Master's Thesis Project**

GitHub Repository:  
🔗 [https://github.com/ArkadiuszCiosek/Investment-Strategies](https://github.com/ArkadiuszCiosek/Investment-Strategies)

---

## 📘 Project Description

This project explores various algorithmic investment strategies, including momentum-based, trend-following, and indicator-driven approaches. It includes backtesting simulations, performance evaluations, and visualizations for multiple financial instruments and time intervals.

The goal is to evaluate how effective selected strategies are over different market conditions and to optimize them for risk-adjusted returns.

---

## 🔧 Setting up the Environment (Anaconda)

### 🧹 If a previous environment already exists:
```bash
# Step 0a: Deactivate the current environment (if active)
conda deactivate

# Step 0b: Remove the existing environment (optional)
conda env remove -n algo-bot

# Step 1: Create the environment from the YAML file
conda env create -f "path\to\environment.yml"

##FOR EXAMPLE:  conda env create -f "C:\Users\Arek\Desktop\Investment Strategies\environment.yml"

# Step 2: Activate the environment
conda activate algo-bot

# Step 3 (Optional - Jupyter Integration)   In jupyter: 
!python -m ipykernel install --user --name=algo-bot --display-name "Python (algo-bot)"





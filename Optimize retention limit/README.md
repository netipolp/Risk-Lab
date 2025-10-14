# Optimize Retention Limit via SAR-Banded Risk Simulation  

### Summary  
This project quantifies how much individual risk exposure (per-life or per-client or per-obligor) for an entity should retain before transferring excess risk. The *retention limit* acts as a self-insurance threshold, balancing capital protection, volatility control, and reinsurance efficiency. The framework simulates portfolio losses using **SAR-banded risk cells** (Sum-At-Risk as the exposure measure) to identify the optimal retention level that meets tail-risk and capital constraints.  

### Files & Data  
- `Retention level optimization.ipynb` — main analysis and simulation notebook  
- `data/mock_client_profile.xlsx` — mock portfolio exposure (age, gender, SAR, etc.) randomly generated for demonstration  
- `data/TMO2017.xlsx` — mortality assumption based on **Thailand Mortality Table 2017 (TMO2017)** published by the [Society of Actuaries of Thailand](https://soat.or.th/en/bulletin-board/mortality-table-2017/85)  

### How to Run  
Open `Retention level optimization.ipynb` in **Google Colab** or **Jupyter Notebook** (with input feed adjustment) and execute all cells sequentially.  
Outputs include retained-loss distributions, VaR/CVaR tables, and retention–capital trade-off curves.  

### References  
- Society of Actuaries of Thailand (SOAT). *Thailand Mortality Table 2017 (TMO2017).*  
- Self-directed research based on publicly available actuarial and quantitative finance sources.  

### Disclaimer  
Research powered by ChatGPT.  
For academic or educational use only.  

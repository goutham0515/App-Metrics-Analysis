This repository contains the analysis of app traffic metrics across six apps, focusing on **idfa_ua_ratio, idfa_ip_ratio, and IVT** (Invalid Traffic). The goal is to understand traffic quality and IVT detection patterns. 🚦

## 🔍 Overview

- **Apps Analyzed:** 6 apps (3 ✅ Valid, 3 ❌ Invalid)  
- **Metrics:**  
  - `idfa_ua_ratio` – IDFA coverage relative to user agents 📱  
  - `idfa_ip_ratio` – IDFA coverage relative to IP addresses 🌐  
  - `IVT` – Invalid traffic percentage ⚠️  

- **Objective:**  
  - Compare trends between Valid and Invalid apps 📈📉  
  - Analyze **why some apps are never marked IVT, while others are flagged earlier or later** ⏰  
  - Identify patterns for monitoring and improving traffic quality 🔎  

## 📂 Contents

- `PPT/` – Slides summarizing trends, IVT timing analysis, and key takeaways 📝  
- `Excel/` – Excel visualizations with line charts for all metrics over time 📊  

## 💡 Key Insights

- Valid apps show **stable metrics and low IVT**, indicating consistent traffic quality ✅  
- Invalid apps show **high fluctuations in metrics and IVT**, flagged at varying times due to traffic anomalies ⚠️  
- **IVT timing patterns:**  
  - Apps with sudden spikes or volatile traffic are flagged earlier 🚨  
  - Apps with stable traffic are not flagged or flagged later ⏳  

## 🛠️ Recommendations

- Monitor traffic volatility to anticipate IVT detection 👀  
- Automate early detection for anomalous traffic patterns 🤖  
- Investigate spikes and irregularities to improve traffic validation 🔧


# Adaptive Centrality Driven Targeted Marketing (ACDTM) Model

The ACDTM (Adaptive Centrality Driven Targeted Marketing) model : an end-to-end framework that integrates social graph analytics and machine learning to optimize influencer targeting and ad campaign performance in digital marketing.

---

**Goal**

To intelligently and efficienly rank influencers and optimize campaign decisions based on their predicted impact on key marketing outcomes: Click-Through Rate (CTR), Conversion Rate, and Customer Lifetime Value (CLV).

---

**Key Features**

- Graph-Based User Network Construction using NetworkX  
- Centrality Score Calculation: Degree, PageRank, Closeness, Betweenness  
- Rich Feature Engineering from user activity, content, and edge interactions  
- Supervised Learning with XGBoost for predicting:
  - CTR
  - Conversion Rate
  - CLV
- Export of top influencers ranked by performance potential  
- Ad Placement Optimization Simulation  
- Performance Monitoring via Visual Comparisons (Actual vs Predicted)

---

**Model Architecture**

The flow follows these major stages:

1. Data Preprocessing  
2. Feature Extraction & Engineering  
3. Graph Construction  
4. Centrality Computation  
5. Feature Selection  
6. Model Training & Evaluation  
7. Campaign Simulation  
8. Feedback Analysis & Performance Visualization

---

**Visualizations**

- Centrality Distributions  
- Top 10 Ranked Influencers by CTR / Conversion / CLV  
- Predicted vs Actual Histograms  
- Scatter Comparisons  

---

**Files**

- `ACDTM.ipynb`: Main notebook containing the full pipeline from preprocessing to export  
- `top_100_influencers.csv`: Top influencers ranked by predicted CTR  
- `top_100_conversion.csv`: Ranked by Conversion Rate  
- `top_100_clv.csv`: Ranked by Customer Lifetime Value  
- `performance_comparison.csv`: Actual vs predicted metrics for all influencers  
- `simulated_underperforming_influencers.csv`: Users with consistent underperformance

---

**Data Sources**

This project uses cleaned and transformed datasets derived from multiple publicly available social/information network datasets and marketing behavior datasets (from SNAP and Kaggle). The input CSV was constructed based on these sources and then processed in alignment with the academic project guidelines.

---

**Requirements**

- Python 3.10+  
- pandas  
- numpy  
- networkx  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost

---

## Contributing

Contributions are welcome!


## License

Distributed under the MIT License.  


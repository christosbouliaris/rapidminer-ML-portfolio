# Decision Tree - Drug Classification (RapidMiner)
##  🎯 Objective 
Train a Decision Tree to classify drug category based on patient attributes.
##  🗂 Data
- Source: `data/drug200 (1).csv` → The dataset used for this analysis.
- Target: `drug` (categorical)
## 🔄 Process (RapidMiner)
1. **Read Data** → set correct file path  
2. **Preprocessing**: handle missing values / encode categoricals (Nominal to Numerical if needed)  
3. **Split Data**: Train/Test (e.g., 70/30, fixed random seed)  
4. **Modeling**: `Decision Tree` operator (criterion: gain_ratio / information_gain)  
5. **Evaluation**: `Apply Model` → `Performance (Classification)`

### Process
![Process](./screenshots/process.png)
### Tree
![Tree](./screenshots/tree.png)
### Performance
![Performance](./screenshots/performance.png)

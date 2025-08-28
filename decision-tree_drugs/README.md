# Decision Tree - Drug Classification (RapidMiner)
##  🎯 Objective 
Train a Decision Tree to classify drug category based on patient attributes.
##  🗂 Data
- Source: `data/drug200 (1).csv` → The dataset used for this analysis.
- Target: `drug` (categorical)
## 🔄 Process (RapidMiner)
- Import data → handle missing values → encode categoricals
- Split train/test (e.g., 70/30)
- **Operator:** Decision Tree with Cross Validation
- Performance: Accuracy, Precision/Recall, Confusion Matrix


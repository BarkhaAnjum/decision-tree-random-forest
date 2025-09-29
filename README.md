
# Decision Tree & Random Forest (Heart Disease Dataset)

### Overview
This project is part of my internship tasks at Elevate Labs.  
It implements **Decision Tree** and **Random Forest classifiers** on the Heart Disease dataset.

### Steps Performed
- Loaded dataset (`heart.csv`).
- Split into training (80%) and testing (20%).
- Trained a **Decision Tree classifier**.
- Controlled overfitting using `max_depth`.
- Trained a **Random Forest classifier** with multiple trees.
- Compared accuracies of both models.
- Visualized the Decision Tree (first 2 levels).
- (Optional) Displayed top feature importances from Random Forest.

### Files
- `Task5_DecisionTree_RandomForest.ipynb` → Notebook with code + outputs.  
- `heart.csv` → Dataset used for training/testing.  
- `README.md` → Project summary.  
- (Optional) `Task5_Report.docx` → Detailed report.

### Results
- Decision Tree accuracy: ~70–80% (depending on depth).  
- Random Forest accuracy: ~80–90% (more stable).  
- Random Forest performed better overall and highlighted key features like chest pain type, age, and cholesterol as important indicators of heart disease.


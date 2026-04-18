## 🚢 Titanic Survival Prediction – Advanced ML Pipeline

A high-performance machine learning solution built for the Titanic Machine Learning from Disaster Kaggle Competition, designed to predict passenger survival using advanced feature engineering, ensemble learning, and model optimization techniques.

---

### 🔍 Overview
This project goes beyond baseline models by implementing a **robust end-to-end ML pipeline**, including:
- Deep feature engineering (Title extraction, family structure, fare segmentation)
- Data preprocessing & missing value handling
- Ensemble modeling with multiple algorithms
- Cross-validation for reliable performance estimation
- Threshold tuning for leaderboard optimization

---

### ⚙️ Tech Stack
- Python (NumPy, Pandas)
- Scikit-learn
- XGBoost
- Kaggle Notebooks

---

### 🧠 Model Architecture
The solution uses a **blended ensemble approach**:
- 🌲 Random Forest (non-linear relationships)
- ⚡ XGBoost (high-performance gradient boosting)
- 📈 Logistic Regression (linear baseline + stability)

Final predictions are generated using **weighted averaging + threshold tuning** for optimal accuracy.

---

### 🧪 Feature Engineering Highlights
- 🎭 Title extraction from names (Mr, Miss, Rare, etc.)
- 👨‍👩‍👧 Family-based features (FamilySize, IsAlone, FamilyType)
- 💰 Fare transformations (FarePerPerson, FareBin, FareLog)
- 🎟 Ticket frequency encoding
- 👶 Age grouping & interaction features (AgeClass, SexPclass)

---

### 📊 Performance
- Cross-Validation Accuracy: **~0.84–0.87**
- Optimized for leaderboard performance using blending and threshold tuning
- Designed to reach **top-tier Kaggle beginner leaderboard scores**

---

### 🚀 Key Learnings
- Importance of feature engineering over model complexity
- Handling missing data effectively
- Ensemble methods outperform single models
- Small tuning (thresholds, weights) can significantly impact results

---

### 📁 Output
Submission file format:
```csv
PassengerId,Survived
892,0
893,1



# 🌲 Forest Cover Type Prediction: A Machine Learning Project 🌲

## 📌 Project Overview
This project focuses on predicting **forest cover types** using the [UCI Covertype dataset](https://archive.ics.uci.edu/dataset/31/covertype).
The dataset contains **581,012 samples** and **54 features**, representing cartographic and environmental attributes.
The task is a **multi-class classification problem** involving **7 forest cover types**.

The model achieved an impressive **94.1% accuracy**, improving significantly from a baseline of 73%.

## 📊 The Challenge
Predicting forest cover types is crucial for:
- **Forest management**
- **Conservation planning**
- **Wildfire risk assessment**
- **Ecological monitoring**

## 🚀 Approach
1. **Data Optimization**
   - Handled severe class imbalance
   - Removed low-variance features

2. **Advanced Modeling**
   - Implemented **Random Forest**, **Gradient Boosting**, and **ensemble methods**

3. **Hyperparameter Tuning**
   - Applied **GridSearchCV** for optimization

4. **Feature Engineering**
   - Created new meaningful features to boost accuracy

## 🎯 Key Results
- ✅ Improved accuracy from **73% → 94.1%** (+21.1% improvement)
- ✅ Identified **Elevation** as the most predictive feature (24.3% importance)
- ✅ Ensemble model outperformed individual algorithms
- ✅ Revealed which forest types are hardest to classify

## 💡 Business Impact
This model enables forestry services to:
- Plan **targeted conservation efforts**
- Assess **wildfire risks** more effectively
- Allocate **resources efficiently**
- Monitor **ecological changes** over time

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **Scikit-learn**
- **Random Forest**
- **Gradient Boosting**
- **Hyperparameter Tuning**
- **Feature Engineering**

## 📂 Dataset
- Source: [UCI Covertype Dataset](https://archive.ics.uci.edu/dataset/31/covertype)
- Samples: **581,012**
- Features: **54**
- Classes: **7 forest cover types**

## ⚙️ Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/forest-cover-type-prediction.git
cd forest-cover-type-prediction
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Download the Dataset
The dataset can be downloaded from [UCI Covertype](https://archive.ics.uci.edu/dataset/31/covertype).
Place the CSV file inside the `data/` directory.

### 5️⃣ Train the Model
```bash
python train.py
```

### 6️⃣ Evaluate the Model
```bash
python evaluate.py
```

### 7️⃣ Make Predictions
```bash
python predict.py --input sample_input.csv
```

## 📌 Future Improvements
- Explore **deep learning approaches** (e.g., neural networks)
- Apply **SMOTE or advanced resampling** for class imbalance
- Optimize further with **automated ML pipelines**

## 📜 License
This project is open-source and available under the **MIT License**.

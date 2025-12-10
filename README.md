
### **Target Variable**
- `exam_score`

### **Feature Types**

#### 🔹 Numerical Features  
- `age`  
- `study_hours`  
- `class_attendance`  
- `sleep_hours`  

#### 🔸 Ordinal Categorical Features  
- `sleep_quality` → poor < average < good < excellent  
- `facility_rating` → low < medium < high  
- `exam_difficulty` → easy < medium < hard  

#### 🔹 Nominal Categorical Features  
- `gender`  
- `course`  
- `internet_access`  
- `study_method`  

---

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **Pandas** – data manipulation  
- **NumPy**  
- **Matplotlib & Seaborn** – visual analysis  
- **Scikit-Learn**  
  - `OrdinalEncoder`  
  - `OneHotEncoder`  
  - `ColumnTransformer`  
  - `StandardScaler`  
  - `train_test_split`  

---

## 📑 Notebook Workflow Summary

### **1. Data Loading & Inspection**
- Inspect first rows with `.head()`  
- Check dataset structure (`.info()`)  
- Identify missing values & duplicates  
- Basic statistics via `.describe()`  

### **2. Exploratory Data Analysis (EDA)**
- Numerical feature distributions  
- Correlation heatmap  
- Category spread & uniqueness checks  

### **3. Preprocessing & Feature Engineering**
- Split dataset into training and testing sets  
- Apply **Ordinal Encoding** with defined category order  
- Apply **One-Hot Encoding** for nominal features  
- Scale numerical features using **StandardScaler**  
- Integrate transformations using **ColumnTransformer**  
- Export final processed feature sets for modeling  

---

## 📦 Output Artifacts

The notebook produces the following key objects:

- `X_train_df` — processed training features  
- `X_test_df` — processed testing features  
- Encoded, scaled, and cleaned datasets  
- Reconstructed feature names  
- A complete preprocessing pipeline ready for ML modeling  

---

## ▶️ How to Use

Clone the repository:

```bash
git clone <your-repo-url>
cd <repository-folder>

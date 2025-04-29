# 🐧 Penguin Clustering Project

This project uses unsupervised machine learning (KMeans clustering) to group Antarctic penguins based on their physical features. The dataset used does not include species labels, so the goal is to identify natural groupings within the data that may correspond to penguin species.

---

## 📂 Project Structure

- `notebook.ipynb` — Jupyter notebook containing the full analysis
- `penguins.csv` — Dataset with penguin measurements
- `README.md` — Project documentation

---

## 📊 Dataset Description

**Source:** Dr. Kristen Gorman, Palmer Station, Antarctica LTER  
**Accessed via:** [DataCamp](https://www.datacamp.com/) Project Platform

**Features:**

| Column              | Description                     |
|---------------------|---------------------------------|
| `culmen_length_mm`  | Culmen (bill) length in mm      |
| `culmen_depth_mm`   | Culmen (bill) depth in mm       |
| `flipper_length_mm` | Flipper length in mm            |
| `body_mass_g`       | Body mass in grams              |
| `sex`               | Penguin sex (MALE/FEMALE)       |

---

## 🔍 Project Steps

1. **Load and Explore Data**  
   Inspect the dataset for structure, missing values, and column types.

2. **Clean Data**  
   Handle missing values to ensure model accuracy.

3. **Preprocess Features**  
   Standardize numeric columns for fair distance-based clustering.

4. **Apply KMeans Clustering**  
   Cluster penguins into 3 groups based on measurements.

5. **Analyze and Visualize Clusters**  
   Compare clustering output with known features and visualize results.

---

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- StandardScaler
- KMeans Clustering

---

## 🎓 Based on DataCamp Learning

This project was completed as part of my learning on **DataCamp**.  
It integrates concepts from multiple courses, such as:

- Data Preprocessing
- Clustering Algorithms
- Data Visualization
- Exploratory Data Analysis (EDA)

> ✅ Proud to apply hands-on skills gained from the DataCamp learning platform.

---

## 🧠 Learning Outcomes

- Exploratory data analysis (EDA)
- Data cleaning and preprocessing
- Unsupervised learning (clustering)
- Feature scaling and dimensionality reduction
- Real-world application of machine learning to biological datasets

---

## 📸 Illustration

![Project Banner](https://imgur.com/orZWHly.png)

---

## 📬 Credits

- Dataset by [Palmer Station Antarctica LTER](https://pal.lternet.edu/)
- Art by [Allison Horst](https://github.com/allisonhorst)
- Project inspired by DataCamp coursework

---


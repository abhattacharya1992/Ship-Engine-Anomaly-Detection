# Ship Engine Anomaly Detection

This project applies statistical methods and unsupervised machine learning to detect 1-5% anomalies in ship engine sensor data—aiming to reduce downtime, safety risks, and inefficiencies in maritime logistics.

Built as part of the **University of Cambridge Data Science, ML and AI Career Accelerator**, it uses IQR, One-Class SVM, and Isolation Forest to flag 1–5% multivariate anomalies, supporting predictive maintenance in real-world supply chain contexts.

📄 **[View Final Report (PDF)](./Bhattacharya_Arunima_CAM_C101_W5_Mini-project.pdf)**  
📓 **[Explore the Jupyter Notebook](./Bhattacharya_Arunima_CAM_C101_W5_Mini_project.ipynb)**

## 🛠️ Tools & Libraries

- **Data processing:** `pandas`, `numpy`
- **Visualisation:** `matplotlib`, `seaborn`
- **Preprocessing:** `StandardScaler`, `MinMaxScaler`  
- **Dimensionality Reduction:** `PCA`
- **Anomaly Detection Algorithms:**
  - Interquartile Range (IQR)
  - **One-Class SVM** (`sklearn.svm.OneClassSVM`)
  - **Isolation Forest** (`sklearn.ensemble.IsolationForest`)

---

### 🚀 Key Techniques

- Unsupervised learning for anomaly detection
- Outlier detection using:
  - Interquartile Range (IQR)
  - One-Class SVM (OCSVM)
  - Isolation Forest
- Feature scaling with StandardScaler and MinMaxScaler
- Dimensionality reduction with PCA
- Visualisation and exploratory data analysis (EDA)

---

## 👩‍💻 Author

**[Arunima Bhattacharya](https://www.linkedin.com/in/arunima-bhattacharya-researcher-phd/)**  
Postdoctoral Researcher | Machine Learning & Data Science Trainee  
Currently enrolled in the Cambridge Career Accelerator (ICE)

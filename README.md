# CyberSecurity Threat Detection using Machine Learning

This project focuses on detecting cybersecurity threats such as unauthorized access, login failures, and suspicious actions by analyzing log data using Machine Learning and Big Data tools.

## 🔗 Reference
GitHub Inspiration: [CyberSecurity-Threat-Detection by DalMakkhani](https://github.com/DalMakkhani/CyberSecurity-Threat-Detection/tree/main)

---

## 📁 Dataset
The dataset used consists of log data with the following fields:
- `timestamp`
- `user`
- `ip_address`
- `action`
- `status`

---

## 💻 Technologies Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Hadoop Ecosystem (HDFS, Hive, Kafka)
- Machine Learning for basic anomaly detection

---

## 🚀 Project Workflow

1. **Data Preprocessing**  
   - Clean and standardize log data
   - Extract key features

2. **Threat Labeling**  
   - Rule-based classification (e.g., status = 'fail' or 'denied' → threat)

3. **Visualization**  
   - Daily threat count
   - IP-wise threat distribution
   - User-wise login failures

---

## 📊 Results
- Generated `is_threat` column to tag suspicious entries
- Created visual plots for insights:
  - Bar plots for IPs with most threats
  - Time-based threat trends
  - Action-based distribution

---

## 📂 Files Included
- `CyberDetection_Round2.ipynb` — Jupyter notebook with full code
- `system_logs.xlsx` — sample input dataset
- `threat_output.csv` — processed output with threat labels
- Visualizations (generated inline in notebook)

---

## 📝 Report & Documentation
The complete project notebook includes:
- Code
- Output
- Visualizations
- Logic explanation

Final submission includes `.ipynb`, output files, and this `README.md` for documentation.

---

## 👩‍💻 Author
**Jagruthi Indurthi**  
GitHub: [Jagruthi-Indurthi](https://github.com/Jagruthi-Indurthi)  
Project for Blackbucks Internship - CyberSecurity Threat Detection using Machine Learning



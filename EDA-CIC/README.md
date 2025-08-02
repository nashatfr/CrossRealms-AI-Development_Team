# AI Integration of BlockShield Project

**Author**: Nashat Alfarajat – BlockShield AI Development Team (Intern)  
**Files**:
- `Task 1 – AI Integration of BlockShield Project.pdf` – Full report
- `CIC-IDS2017 EDA.ipynb` – Jupyter notebook with exploratory data analysis

---

## 📌 Overview

This task focuses on the **exploratory data analysis (EDA)** of the **CIC-IDS-2017 dataset**, as part of the AI development efforts for the BlockShield cybersecurity platform.

**BlockShield** is developed by **CrossRealms International** to track and block malicious IPs across global networks using intelligent threat detection techniques.

---

## 📊 Why This Dataset?

The **CIC-IDS-2017** dataset was chosen for its:
- ✅ Real-world relevance in intrusion detection research
- ✅ High-quality labeled data
- ✅ Large size: **2,660,377** records and **85 features**
- ✅ Diversity of attack types

Attack types covered include:
- DDoS, PortScan, Bot, Infiltration  
- FTP-Patator, SSH-Patator  
- DoS Slowloris, DoS Hulk, DoS GoldenEye, DoS Slowhttptest  
- Heartbleed  
- Benign traffic

---

## 📁 What’s in the Dataset?

Each row represents a network flow and includes:

- **Time-based features**: Useful for time-series or sequential modeling  
- **IP and Port details**: Source & destination behavior analysis  
- **Traffic metrics**: Flow duration, byte counts, packet stats  
- **Protocol and flag data**: Low-level behavior indicators  
- **Labels**: Multiclass and binary classification targets

---

## ✅ Current Progress

Initial preprocessing steps completed:
- ✔️ Missing value handling  
- ✔️ Duplicate removal  
- ✔️ Outlier detection and treatment  

---

## 🔜 Next Steps

The following will be addressed during modeling:
- 🔧 Scaling and normalization  
- 🔧 Feature selection & engineering  
- 🤖 Model training and evaluation (binary & multiclass)

---


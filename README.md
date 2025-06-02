# task1_medical_appointments
The task focuses on medical appointments in Brazil to find out why some appointments result in a 'no_show'
---

## 📌 Dataset Summary

- **Rows:** 110,527  
- **Columns:** 14  
- **Target variable:** `no_show` (Yes/No)
---

## 🔧 Data Cleaning Tasks
- Handled missing values
- Removed duplicates (none found)
- Cleaned column names (lowercase, underscores)
- Converted scheduled_day and appointment_day to datetime
- Mapped no_show from 'yes'/'no' to 1/0 and converted to int
- Standardized gender values (mapped to 0/1)
- Handled invalid age values (e.g., replaced -1 with median)
- Encoded neighbourhood (now numerical)
---

## 📊 Tools Used

- Python (Pandas, NumPy, Sklearn)
- Jupyter Notebook
---

## 📁 Dataset Source

[Medical Appointment No Shows – Kaggle](https://www.kaggle.com/datasets?search=Medical+Appointment+No+Shows)

---


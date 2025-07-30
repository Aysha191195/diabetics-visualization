# 🩺 Diabetic Health Data Visualization

This project visualizes a large health dataset with 100,000 patient records, aiming to uncover insights into diabetes risk based on medical and lifestyle factors. The notebook contains detailed visual analysis using Python libraries.

## 📊 Project Highlights

- Visual exploration of diabetes prevalence
- Feature-wise comparison: age, gender, hypertension, heart disease, BMI, etc.
- Correlation analysis and outlier detection
- Clear, readable visualizations using Seaborn and Matplotlib

## 🧾 Dataset Features

| Column               | Description                            |
|----------------------|----------------------------------------|
| `gender`             | Male / Female                          |
| `age`                | Patient's age                          |
| `hypertension`       | 1 = Yes, 0 = No                        |
| `heart_disease`      | 1 = Yes, 0 = No                        |
| `smoking_history`    | never / current / former / No Info     |
| `bmi`                | Body Mass Index                        |
| `HbA1c_level`        | Hemoglobin A1c level                   |
| `blood_glucose_level`| Blood sugar (mg/dL)                    |
| `diabetes`           | Target label: 1 = Diabetes, 0 = No     |

## 📁 Repository Structure

📦 diabetics-visualization
├── data/
      dataset.csv
├── Notebook/
     diabetics_dataset.ipynb
├── README.md



## 📦 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `jupyter`
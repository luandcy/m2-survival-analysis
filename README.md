# m2-survival-analysis 🧪

**Survival Analysis**

This project aims to implement survival models on a **prison recidivism dataset** with strong right-censoring. We implement models such as **Cox**, **Random Forest**, and **Regularized Cox**.  

---

## Dataset 📊

The dataset comes from **Rossi (1980)**, covering **432 individuals convicted of theft in Maryland** during the 1970s. Each individual is followed for **52 weeks after release**, tracking whether they recidivate. Individuals are divided into two groups based on whether they received **financial aid from the government** during the study period.  

**Sources & Documentation:**  
- Rossi dataset documentation

---

## Project Overview 🚀

This project focuses on **analyzing survival times** and modeling **recidivism risk**. We implemented:

- **Kaplan-Meier estimators** for survival probability visualization  
- **Cox proportional hazards models**, including **regularized versions**  
- **Random Forest survival models**  
- **Brier score evaluation** for model prediction accuracy  
- **Calibration plots** to compare predicted vs. observed survival  

---

## Key Findings 🔑

- Survival probabilities differ depending on whether individuals received financial aid.  
- Model performance tends to decrease over time, with early predictions being more reliable.  
- Analyzing multiple performance metrics is highly recommended, as it provides a **more complete overview of model performance**.  


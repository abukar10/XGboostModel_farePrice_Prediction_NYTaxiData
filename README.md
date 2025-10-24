<p align="center">
  <img src="https://github.com/abukar10/XGboostModel_farePrice_Prediction_NYTaxiData/blob/main/outlier_detection.PNG" 
       alt="Outlier Analysis - NYC Taxi" width="90%">
</p>

<p align="center"><i>Outlier Analysis — 5 Million NYC Taxi Trip Data Points</i></p>


<h1 align="center">🚕 NYC Taxi XGBoost Lab</h1>
<h3 align="center">GPU-accelerated machine learning workflow on 2023 NYC Yellow Taxi data using XGBoost and RAPIDS (cuDF, RMM)</h3>

---

## 🗽 Overview
This project demonstrates how to train an **XGBoost regression model** on **NYC Yellow Taxi trip data** using **Google Colab**, leveraging GPU acceleration via **RAPIDS cuDF** and **RMM** for high-performance data processing.

---

## 🚀 How to Run
1. Open the notebook in Google Colab:  
   → [NYC_Taxi_XGBoost_Abukar.ipynb](./NYC_Taxi_XGBoost_Abukar.ipynb)
2. Run all cells step-by-step.  
3. Mount your Google Drive when prompted so data and results persist.  
4. Due to the dataset’s large size, it cannot be hosted here. Please upload the raw data to your Google Drive (same folder as this notebook).  
5. Once uploaded, confirm that the **dataset path** in the notebook matches your Drive path.  

---

## 📦 Dataset
The project uses **NYC Yellow Taxi Trip Records** provided by the **New York City Taxi & Limousine Commission (TLC)**.  
You can download the dataset directly from the city’s open-data portal:

- **5 Million sample (August 2015):**  
  [https://data.cityofnewyork.us/resource/2yzn-sicd.csv?$limit=5000000](https://data.cityofnewyork.us/resource/2yzn-sicd.csv?$limit=5000000)

- **Full yearly datasets:**  
  [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

After downloading, place the file in your Google Drive in the same folder as this notebook (`.ipynb`).

---

## 🧾✨ **Acknowledgments**

> This repository builds upon the open educational project developed by **[Mariya Sha](https://github.com/MariyaSha)**,  
> as part of the **[Python Simplified](https://www.youtube.com/@PythonSimplified)** YouTube learning initiative.  

The foundational implementation — including the data ingestion pipeline, GPU-accelerated processing with **RAPIDS cuDF**,  
and model training using **XGBoost** — originates from her publicly available instructional materials.  

💡 **This version extends the original project with:**  
- 📊 Enhanced **visualizations** to identify and interpret **anomalies and outliers** in the NYC Yellow Taxi dataset  
- ⚙️ Minor workflow optimizations for **Google Colab** compatibility and improved reproducibility  

All credit for the original concept, structure, and educational design belongs to  
**Mariya Sha** and the **Python Simplified** team.  

> 🧠 *This derivative work is intended solely for educational and exploratory purposes.*

---

### 🔑 **Keywords**
`machine learning`, `data science`, `xgboost`, `cudf`, `rapids`, `python`, `pandas`, `gpu acceleration`,  
`anomaly detection`, `big data`, `nyc taxi`, `portfolio project`, `google colab`, `ai visualization`, `python simplified`

---

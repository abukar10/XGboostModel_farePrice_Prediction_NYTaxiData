# 🗽 NYC Taxi XGBoost Lab

This project demonstrates how to train an XGBoost regression model on NYC Yellow Taxi trip data using Google Colab.

---

## 🚀 How to Run
1. Open the notebook in Google Colab:
   - [NYC_Taxi_XGBoost_Abukar.ipynb](./NYC_Taxi_XGBoost_Abukar.ipynb)
2. Run all cells step-by-step.
3. Mount your Google Drive when prompted so data and results persist.

---

## 📦 Dataset

The project uses **NYC Yellow Taxi Trip Records** provided by the NYC TLC.  
You can download the dataset directly from the city’s open-data portal:

- **5 Million sample (August 2015):**  
  [https://data.cityofnewyork.us/resource/2yzn-sicd.csv?$limit=5000000](https://data.cityofnewyork.us/resource/2yzn-sicd.csv?$limit=5000000)

- **Full yearly datasets:**  
  [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

After downloading, place the file in your Google Drive (in the same folder as the ipynb file)

🧾 Acknowledgments

This repository builds upon the open educational project developed by Mariya Sha
 as part of the Python Simplified
 YouTube learning initiative.
The foundational implementation — including the data ingestion pipeline, GPU-accelerated processing with RAPIDS cuDF, and model training using XGBoost — originates from her publicly available instructional materials.

This version extends the original project with:

Additional data visualization tools to highlight and interpret anomalies and outliers in the NYC Yellow Taxi dataset

Minor workflow refinements for improved performance and reproducibility within Google Colab

All credit for the original concept, structure, and educational design belongs to Mariya Sha and the Python Simplified team.
This derivative work is intended solely for educational and exploratory purposes.

🔑 Keywords

machine learning, data science, xgboost, cudf, rapids, python, pandas, gpu acceleration, anomaly detection, big data, nyc taxi, portfolio project, google colab, ai visualization, python simplified

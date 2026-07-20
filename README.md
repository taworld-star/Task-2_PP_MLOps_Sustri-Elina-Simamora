# SISTECH 2026 — MLOps Hands-On 2
## Risk Score Prediction: Modeling & Continual Learning

**Nama:** Sustri Elina Simamora  
**Role:** Peserta SISTECH 2026 — MLOps Track  

---

###  Deskripsi Proyek

Proyek ini merupakan kelanjutan dari Hands-On 1. 
Membangun **sistem prediksi Risk Score** (0-100) berbasis data kejahatan Chicago menggunakan pendekatan MLOps yang terstruktur:

1. **Baseline** — patokan minimal (median predictor)
2. **Feature Vector Assembly** — scaling & encoding fitur
3. **Model Training** — Linear Regression, Random Forest, XGBoost
4. **Evaluation** — MAE, RMSE, R² dengan perbandingan baseline
5. **Continual Learning** — drift detection (PSI), retraining bersyarat
6. **Model Versioning** — registry dengan metadata lengkap

---

###  Struktur Repositori
── task_2_pp_mlops_sustri_elina_simamora.ipynb
├── features_labels.csv # Dataset dari HO1
├── model_registry.json # Rekam jejak versi model
├── model_registry.csv # Registry dalam CSV
├── scaler.pkl # Scaler untuk serving
├── checkpoints/ # Folder model .pkl
│ ├── model_v0.pkl
│ ├── scaler_v0.pkl
│ ├── model_v1.pkl
│ └── scaler_v1.pkl
├── README.md # Dokumentasi proyek





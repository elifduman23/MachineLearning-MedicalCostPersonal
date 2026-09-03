# Health Insurance Cost Prediction / Sağlık Sigortası Maliyet Tahmini

## 🇬🇧 English
### Project Overview
This repository contains an end-to-end Machine Learning project aimed at predicting medical insurance charges based on patient demographics and health metrics. 

### Technologies Used
- **Language:** Python (Kaggle Notebook)
- **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-Learn

### Workflow
1. **Exploratory Data Analysis (EDA):** Analyzed feature distributions and correlations (e.g., BMI and smoking status vs. charges).
2. **Data Preprocessing:** Applied One-Hot Encoding to categorical variables (`sex`, `smoker`, `region`).
3. **Data Splitting:** 80/20 train-test split (`random_state=42`).
4. **Modeling:** Trained a Linear Regression model.
5. **Evaluation:** Assessed model performance using regression metrics and actual vs. predicted scatter plots.

### Model Performance (Linear Regression)
- **R² Score:** 0.7836
- **MAE:** $4,181
- **RMSE:** $5,796

---

## 🇹🇷 Türkçe
### Proje Özeti
Bu depo, hastaların demografik ve sağlık verilerini kullanarak tıbbi sigorta masraflarını tahmin etmeyi amaçlayan uçtan uca bir Makine Öğrenmesi projesini içermektedir.

### Kullanılan Teknolojiler
- **Dil:** Python (Kaggle Notebook)
- **Kütüphaneler:** Pandas, Seaborn, Matplotlib, Scikit-Learn

### İş Akışı
1. **Keşifsel Veri Analizi (EDA):** Özelliklerin dağılımı ve korelasyonları incelendi (örn. Vücut Kitle İndeksi (BMI), sigara kullanımı ve masraf ilişkisi).
2. **Veri Ön İşleme:** Kategorik değişkenlere (`sex`, `smoker`, `region`) One-Hot Encoding uygulandı.
3. **Veri Bölme:** Veri seti %80 eğitim, %20 test olarak ayrıldı (`random_state=42`).
4. **Modelleme:** Lineer Regresyon (Linear Regression) modeli kullanılarak eğitildi.
5. **Değerlendirme:** Model performansı hata metrikleri ve gerçek/tahmin edilen değerlerin saçılım grafiği (scatterplot) ile analiz edildi.

### Model Performansı (Lineer Regresyon)
- **R² Skoru:** 0.7836
- **MAE (Ortalama Mutlak Hata):** 4.181 $
- **RMSE (Kök Ortalama Kare Hata):** 5.796 $

# 🏎️ Formula 1 Historical Analytics Dashboard (1950–2025)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Business%20Intelligence-blue?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## 📋 Layihə Haqqında
Bu layihə **1950-ci ildən 2025-ci ilə qədər** olan Formula 1 yarış tarixini, sürücü performanslarını, komanda (constructor) nəticələrini və pit-stop səmərəliliyini hərtərəfli təhlil edən interaktiv biznes analitika panelidir. Layihənin əsas məqsədi böyük həcmli tarixi idman məlumatlarını vizuallaşdırmaq və müxtəlif illər üzrə statistika müqayisələrini aparmaqdır.

---

## 🛠️ İstifadə Olunan Texnologiyalar və Metodologiya
* **Data Visualization & BI:** Power BI Desktop
* **Data Modeling:** Star Schema (Ulduz sxemi arxitekturası)
* **Data Transformation (ETL):** Power Query (Məlumatların təmizlənməsi, formatlanması və əlaqələndirilməsi)
* **Calculations:** Qabaqcıl DAX (Data Analysis Expressions) funksiyaları və ölçüləri (Measures)

---

## 📊 Dashboard-un Əsas Xüsusiyyətləri və Bölmələri
Hesabat aşağıdakı əsas analitik istiqamətləri əhatə edir:
1. **Driver Standings & Performance:** Sürücülərin illər üzrə qələbə sayı, podium göstəriciləri və xal toplama dinamikası.
2. **Constructor Standings:** Mühəndislik və komanda sıralamalarının illik müqayisəsi.
3. **Race Results & Circuit Analytics:** Yarışların keçirildiyi treklər (circuits), finiş göstəriciləri və qəza/tərk etmə (DNF) statistikaları.
4. **Pit Stop Efficiency:** Komandaların pit-stop sürətləri və zaman optimizasiyası analizi.

---

## 📈 Əsas İnsaytlar və Nəticələr
* Tarixi olaraq ən çox çempionluq qazanan sürücülərin illər üzrə performans trayektoriyaları müəyyən edildi.
* Komandaların pit-stop səmərəliliyi ilə yarış nəticələri arasındakı güclü əlaqə vizuallaşdırıldı.
* Müxtəlif dövrlər üzrə texnoloji dəyişikliklərin yarış sürətinə təsiri təhlil olundu.

---

## 📂 Layihənin Strukturu
```text
F1-Project/
│
├── F1 dashboard/        # Power BI hesabat faylı (.pbix)
├── F1 dataset/          # Təmizlənmiş məlumat bazası (.csv / .xlsx)
├── F1 images/           # Dashboard skrinşotları və vizuallar
├── LICENSE              # MIT Lisenziyası
└── README.md            # Layihənin təsvir sənədi

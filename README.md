# car_price_prediction
# 🚗 Car Price Prediction (Machine Learning)

Ushbu loyiha avtomobillarning texnik xususiyatlari (yili, yurgan masofasi, dvigatel hajmi va h.k.) asosida ularning bozor narxini bashorat qilish uchun qurilgan.

## 📌 Loyiha maqsadi
Ma'lumotlar tahlili va Machine Learning algoritmlari yordamida avtomobil narxini aniqlovchi model yaratish. Loyiha davomida xalqaro avtomobil bozori ma'lumotlaridan foydalanilgan.

## 🛠 Ishlatilgan texnologiyalar
* Dasturlash tili: Python
* Kutubxonalar: * Pandas va NumPy - ma'lumotlarni qayta ishlash uchun.
    * Matplotlib va Seaborn - vizualizatsiya uchun.
    * Scikit-learn - model qurish va baholash uchun.

## 🚀 Model haqida
Loyiha doirasida Random Forest Regressor algoritmi ishlatildi. 
* Model aniqligi (R2 Score): 0.81 (yoki o'zingizda chiqqan natija)
* RMSE: 6601.5

## 📊 Jarayon bosqichlari
1. Data Cleaning: Ustunlardagi matnlarni raqamga o'tkazish (Mileage, Engine volume).
   ![Narxlar taqsimoti]
    * (https://private-user-images.githubusercontent.com/239104917/579413271-e78e7cb3-43c4-49f6-9489-684cddb64a1d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzYzNjE4MTksIm5iZiI6MTc3NjM2MTUxOSwicGF0aCI6Ii8yMzkxMDQ5MTcvNTc5NDEzMjcxLWU3OGU3Y2IzLTQzYzQtNDlmNi05NDg5LTY4NGNkZGI2NGExZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQxNlQxNzQ1MTlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01N2RkM2NhZDIwMDM3MjU0NzBiYmJmYTJiMWIzODBmZDBkMThmNzdkMTEzZTJmZTU2MTYwN2E3MjY3YWNiMjcwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.X7bTQpKyWgcQg2aLeGIbGxVN0XGb8AqRGeWhkm4D3b4)

2. EDA: Narx va boshqa omillar o'rtasidagi bog'liqlikni grafiklarda tahlil qilish.
3. Preprocessing: Kategoriyali ustunlarni One-Hot Encoding yordamida raqamga o'tkazish.
4. Modeling: Modelni o'qitish va bashorat qilish.

## 📂 Fayllar tarkibi
* car_model.ipynb - Asosiy kodlar va tahlillar.
* car_price_prediction.csv.zip - Loyiha uchun ishlatilgan dataset.

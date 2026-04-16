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
2. EDA: Narx va boshqa omillar o'rtasidagi bog'liqlikni grafiklarda tahlil qilish.
3. Preprocessing: Kategoriyali ustunlarni One-Hot Encoding yordamida raqamga o'tkazish.
4. Modeling: Modelni o'qitish va bashorat qilish.

## 📂 Fayllar tarkibi
* car_model.ipynb - Asosiy kodlar va tahlillar.
* car_price_prediction.csv.zip - Loyiha uchun ishlatilgan dataset.

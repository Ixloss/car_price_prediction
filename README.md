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
<img width="705" height="393" alt="Mashina narx taqsimoti" src="https://github.com/user-attachments/assets/81c89962-69e3-4b97-8a08-5d2bd1047824" />

3. EDA: Narx va boshqa omillar o'rtasidagi bog'liqlikni grafiklarda tahlil qilish.

![Narx va yil bog'liqligi]
<img width="876" height="547" alt="Ishlab chiq yili va narxi" src="https://github.com/user-attachments/assets/22c32e26-c8c0-460a-acc9-d133a8cce3dc" />

4. Preprocessing: Kategoriyali ustunlarni One-Hot Encoding yordamida raqamga o'tkazish.
5. Modeling: Modelni o'qitish va bashorat qilish.

![Model bashorati]
<img width="890" height="547" alt="Model bashorat grafigi" src="https://github.com/user-attachments/assets/25b0c714-f49a-43ad-b00b-100d957470f0" />

## 📂 Fayllar tarkibi
* car_model.ipynb - Asosiy kodlar va tahlillar.
* car_price_prediction.csv.zip - Loyiha uchun ishlatilgan dataset.

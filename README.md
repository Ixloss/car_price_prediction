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
(https://private-user-images.githubusercontent.com/239104917/579413271-e78e7cb3-43c4-49f6-9489-684cddb64a1d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzYzNjQyNDAsIm5iZiI6MTc3NjM2Mzk0MCwicGF0aCI6Ii8yMzkxMDQ5MTcvNTc5NDEzMjcxLWU3OGU3Y2IzLTQzYzQtNDlmNi05NDg5LTY4NGNkZGI2NGExZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQxNlQxODI1NDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mMDE2NzFlOGE0MzZhMzA2OWRlMDViODg3MDBjMWRiYjlmMzRjMjlmMjFlY2RmMjc2ZWM1ZTI1NTRjZjI3MmEzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.wjRoZ8pHjQf10JltU09IfrGkpgq2sCTPakcS7hlQ15U)
<img width="705" height="393" alt="Mashina narx taqsimoti" src="https://github.com/user-attachments/assets/81c89962-69e3-4b97-8a08-5d2bd1047824" />


3. EDA: Narx va boshqa omillar o'rtasidagi bog'liqlikni grafiklarda tahlil qilish.

![Narx va yil bog'liqligi]
(https://private-user-images.githubusercontent.com/239104917/579413317-4ff1c833-2f40-4997-81bb-51ad33ae3b5d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzYzNjQzODgsIm5iZiI6MTc3NjM2NDA4OCwicGF0aCI6Ii8yMzkxMDQ5MTcvNTc5NDEzMzE3LTRmZjFjODMzLTJmNDAtNDk5Ny04MWJiLTUxYWQzM2FlM2I1ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQxNlQxODI4MDhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lYzEzZjIzNWFjNWQ3Y2QzOGU1NDAzYjIyYjYzNWUyYzEwZThjZDUzMTVhNWU3MWJjOWYwYmE3OWMyNTEwMmQ4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.MBsLRPzeGMgWZskt7Sgc3DDzA0ENKA8iDqFCgc_BfLo)
<img width="876" height="547" alt="Ishlab chiq yili va narxi" src="https://github.com/user-attachments/assets/22c32e26-c8c0-460a-acc9-d133a8cce3dc" />


4. Preprocessing: Kategoriyali ustunlarni One-Hot Encoding yordamida raqamga o'tkazish.
5. Modeling: Modelni o'qitish va bashorat qilish.

![Model bashorati]
(https://private-user-images.githubusercontent.com/239104917/579413365-2fa560bc-4a01-449a-be9e-c76cc71142af.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzYzNjQ0MjgsIm5iZiI6MTc3NjM2NDEyOCwicGF0aCI6Ii8yMzkxMDQ5MTcvNTc5NDEzMzY1LTJmYTU2MGJjLTRhMDEtNDQ5YS1iZTllLWM3NmNjNzExNDJhZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNDE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDQxNlQxODI4NDhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kYzE5N2QzNzM3YTBkNDliNDQxNTgzYzc1YmZmYjViYzc3NDUwZTZmZTA0YzNjNjU2ZTA1OTY5MDkyNGIyNGY5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.pxAGCMNsD2ysw82he-Bc3bBA4e2Ue0qnpTDc4JSr7zM)
<img width="890" height="547" alt="Model bashorat grafigi" src="https://github.com/user-attachments/assets/25b0c714-f49a-43ad-b00b-100d957470f0" />


## 📂 Fayllar tarkibi
* car_model.ipynb - Asosiy kodlar va tahlillar.
* car_price_prediction.csv.zip - Loyiha uchun ishlatilgan dataset.

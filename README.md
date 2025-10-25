# 🌍 Hava Kalitesi İzleme Sistemi

Arduino tabanlı bir sensör sistemiyle gerçek zamanlı hava kalitesi verilerini ölçen ve bu verileri bir **Telegram botu** aracılığıyla kullanıcılara sunan açık kaynaklı bir projedir.

---

## 🤖 Telegram Botları

📲 Hemen dene: [https://t.me/HavaQBot](https://t.me/HavaQBot)

📲 Hemen dene: [https://t.me/DBFLHisBot](https://t.me/DBFLHisBot)

Bot üzerinden aşağıdaki bilgileri sorgulayabilirsin:

- PM2.5 / PM10 partikül yoğunluğu
- Karbon monoksit (CO) seviyesi
- Azot dioksit (NO₂) seviyesi
- Sıcaklık ve nem bilgisi
- Ölçüm yapılan konum ve zaman

---

## ⚙️ Donanım Bileşenleri

| Bileşen | Açıklama |
|--------|----------|
| Arduino Mega 2560 | Kontrol kartı |
| PMS5003 | PM2.5/PM10 partikül sensörü |
| MQ7 / MQ135 | CO / CO₂ gaz sensörleri |
| DHT11 | Sıcaklık ve nem sensörü |
| GPS Modülü | Konum tespiti |
| SD Kart / Wi-Fi Modülü | Veri kaydı ve aktarımı |

---

## 🧠 Nasıl Çalışır?

1. Sensörlerden ölçümler alınır
2. Veriler SD karta yazılır veya Wi-Fi ile veritabanına aktarılır
3. Telegram bot, veritabanından bu verileri sorgular
4. Kullanıcının komutuna göre anlık ölçüm bilgisi sunulur

---

## 🔐 Şartlar ve Koşullar

Botları kullanarak [Şartlar ve Koşullar](https://github.com/ardaulger/havaq-map/blob/main/terms_conditions.md) (https://github.com/ardaulger/havaq-map/blob/main/terms_conditions.md)  tüm maddeleri kabul etmiş sayılırsınız.

---

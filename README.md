# Black-Swan V1.0 | Wireless Biomedical & Seismic Sensor Node

Black-Swan V1.0, saha verilerini işlemek ve uzun menzilli kablosuz ağlar üzerinden aktarmak için geliştirdigim, düşük güç tüketimli bir "Edge" sensör düğümüdür. Proje kapsamında, biyomedikal sinyal işleme (AFE) yeteneklerini savunma sanayii standartlarında RF güvenilirliği ile tek bir PCB üzerinde birleştirmeyi hedefledim.

## Teknik Özellikler

* **Mikrodenetleyici (MCU):** STM32L431RCT6 (Ultra-Low Power ARM Cortex-M4).
* **Kablosuz Haberleşme (RF):** SX1278 LoRa modülü entegrasyonu ve 50 $\Omega$ empedans uyumlu SMA anten çıkışı.
* **Analog Ön Uç (AFE):** EKG, EMG veya sismik veriler için optimize edilmiş 3-Op-Amp enstrümantasyon amplifikatörü.
* **Atalet Sensörü (IMU):** 6-eksenli hareket takibi için entegre MPU-6050.
* **Güç Yönetimi:** USB-C üzerinden besleme hattı ve gürültü regülasyonu için molded güç indüktörü (L1).

## Proje Yapısı

* `/Hardware`: KiCad şematik (.kicad_sch) ve PCB (.kicad_pcb) tasarım dosyaları.
* `/Hardware/BOM`: Malzeme listesi ve bileşen detayları.
* `/Docs`: Tasarım raporları ve 3D render görselleri.

## Tasarım Kararları

RF bütünlüğü ve analog sinyal kalitesini korumak adına genel amaçlı genişleme portlarını V2.0 sürümüne planladım.

---
**Hazırlayan:** Göktan Sarıkan (Yıldız Teknik Üniversitesi)
**Tarih:** Mart 2026

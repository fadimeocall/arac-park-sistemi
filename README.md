# ARDUINO ARAÇ PARK SİSTEMİ
<img src="./content/arduino_uno_sensör.png" width="1200px"><br>

## ## 📋 Proje Tanımı

Bu proje, araçların park ederken yakın çevredeki nesneleri algılamasına yardımcı olan bir **park destek sistemi (PAEK sistemi)**dir. Arduino UNO, **HC-SR04 ultrasonik sensör** ve **pasif buzzer** kullanılarak geliştirilmiştir. Sistem, yakındaki bir nesneyi algıladığında buzzer ile sesli uyarı verir. Nesneye yaklaşıldıkça uyarı sesi daha hızlı hale gelir.

Proje, **Arduino ile elektronik temellerini öğrenmek isteyen herkes için uygundur.** Basit bağlantılarla gerçek dünyada işlevsel bir sistem inşa etmek hedeflenmiştir.

---

## ## 📋 Sistem Gereksinimleri (GÜNCEL)
🖥️ Yazılım:
Arduino IDE (en son sürüm)

Arduino sürücüleri (genellikle IDE kurulunca otomatik gelir)

Bilgisayarınızda USB portu olmalı

⚙️ Kurulum Adımları:
Arduino IDE’yi kurduktan sonra Arduino UNO kartınızı USB ile bilgisayara bağlayın.

Arduino IDE içinde:

Araçlar > Kart > Arduino Uno seçin

Araçlar > Port > COM3 ya da COM4 gibi Arduino'nun bağlı olduğu portu seçin (kart takıldığında otomatik görünür)

Kodu yapıştırın, ardından Yükle (Upload) butonuna tıklayın.

Eğer “Seri Port” hatası alırsanız kabloyu değiştirin ya da COM ayarını kontrol edin.

🔌 Not: USB kablosu sadece güç vermekle kalmaz, veri aktarımı da sağlar. Mutlaka data kablosu (hem güç hem veri taşıyan) kullanılmalıdır.


## 📂 Proje Yapısı

PAEK-Park-Sensoru/
├── README.md                   <- Proje açıklamaları (bu dosya)
├── (arac-park-sistemi.ino)     <- Arduino kodları
└── images/
    └── arduino_uno_sensör.png  <- Bağlantı şeması görseli




## ## 🧠 Geliştirici
Fadime ÖCAL
📚 YBS Öğrencisi
💡 Arduino & Web teknolojilerine ilgi duyuyor
📍 Türkiye, 2025

## ##🔄 Geliştirme Önerileri
Bu projeyi daha ileriye taşımak istersen:

📺 LCD ekran ile mesafeyi sayısal olarak gösterebilirsin.

🌈 RGB LED’ler ile renkli uyarı sistemi kurabilirsin (örneğin kırmızı – tehlike).

📱 Bluetooth modülü ekleyerek mesafeyi mobil uygulamada gösterebilirsin.


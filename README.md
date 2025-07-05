# ⚡ ESC PCB Tasarımı (Electronic Speed Controller) – Brushless Motor Sürümü

Bu proje, fırçasız (BLDC) motorlar için özel olarak tasarlanmış **ESC (Electronic Speed Controller)** devresinin PCB tasarımını içermektedir. Yüksek verimlilik, termal denge ve kompakt boyut dikkate alınarak hazırlanmış bu kart, drone, RC araçlar ve endüstriyel motor kontrol projeleri için kullanılabilir.

---

## 🔧 Teknik Özellikler

- 🌀 **3 Fazlı BLDC Motor Sürme Desteği**
- 💥 **IR2101 MOSFET Sürücü Entegresi** kullanımı
- 🔺 **N-kanal MOSFET’lerle yüksek akım kontrolü**
- 🔁 **PWM giriş kontrolü için mikrodenetleyici uyumlu**
- 🌡️ Düşük ısı yayılımı ve termal denge için optimize edilmiş layout
- ⚙️ Proteus ile simülasyon, Altium Designer ile 4 katmanlı PCB tasarımı

---

## 🔍 Kullanılan Bileşenler

- **IR2101** – Yüksek/Alçak taraf sürücü
- **IRLR7843** – MOSFET
- **Gate dirençleri, diyotlar, kapasitörler**
- **Shunt direnç (opsiyonel)** – Akım algılama
- **Harici MCU (ATMEGA328P) ile kontrol edilebilir**

## 📁 Dosya İçeriği

├── Gerber/
│ └── üretime hazır gerber dosyaları
├── Schematic/
│ └── ESC_Schematic.SchDoc
├── PCB/
│ └── ESC_Layout.PcbDoc
├── Simulation/
│ └── Proteus ESC test dosyası
└── README.md


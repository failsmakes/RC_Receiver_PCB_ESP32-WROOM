# MakerZ RC Receiver PCB for ESP32-WROOM

Bu proje, [RC-Receiver-ESP](https://github.com/failsmakes/RC-Receiver-ESP) yazılımı için tasarlanmış **ESP32-WROOM tabanlı RC alıcı devresinin PCB çizimini** içerir. Tasarım **KiCad 10.0.1** ile hazırlanmıştır.

## 📌 Proje Özeti
Bu kart, RC sinyallerini ESP32 üzerinden işleyebilmek için optimize edilmiştir. Üzerinde güç regülasyonu, servo ve motor çıkışları, MPU6050 sensör bağlantısı ve MP1584 voltaj modülü için yerleşim alanları bulunur.

## 🧩 Teknik Bileşenler
- **ESP32-WROOM-32 DevKit V1**  
- **MP1584 DC-DC Regülatör Modülü**  
- **MPU6050 IMU Sensör Modülü**  
- **Servo ve Motor çıkış pinleri**  
- **Güç girişleri:** +BATT, +5V, GND  
- **Bağlantı pinleri:** SDA, SCL, INT, VCC  

## 📂 Dosya İçeriği
- `RC_Receiver_PCB_ESP32-WROOM.kicad_pcb` → PCB çizimi  
- `RC_Receiver_PCB_ESP32-WROOM.sch` → Şematik dosyası  
- `MakerZ RC Receiver ESP32 WROOM Schematic.pdf` → Şema PDF çıktısı  
- `gerber/` → Üretim dosyaları  
- `README.md` → Bu açıklama dosyası  

## 🖼️ PCB Görselleri
### Üst Katman
![PCB Top View](../../images/RC_Receiver_PCB_ESP32-WROOM1.png)

### Alt Katman
![PCB Bottom View](../../images/RC_Receiver_PCB_ESP32-WROOM2.png)

## 🚀 Kullanım
1. KiCad ile açarak şematik ve PCB tasarımını inceleyin.  
2. `gerber/` klasöründeki dosyaları kullanarak PCB üretimi yaptırabilirsiniz.  
3. ESP32-WROOM modülünü ve gerekli komponentleri lehimleyerek RC-Receiver-ESP yazılımını yükleyin.  

## 🔗 İlgili Proje
Bu PCB tasarımı, [RC-Receiver-ESP](https://github.com/failsmakes/RC-Receiver-ESP) yazılım projesi ile birlikte kullanılmak üzere hazırlanmıştır.

## 📜 Lisans
Bu proje açık kaynaklıdır. Detaylar için lisans dosyasına göz atın.

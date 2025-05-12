# Amateur Radio Experiments for Space (TC3ATA)

This repository serves as an open-source initiative for amateur radio, APRS, pico balloons, and CubeSat experiments. It provides a structured learning path for enthusiasts, researchers, and students.  

https://www.qrz.com/db/TC3ATA
https://www.qrz.com/db/TB3FLY

## Project Overview

- **Skill Level:** Beginner to Advanced  
- **Topics Covered:** Amateur radio, APRS, pico balloons, satellite communications, CubeSat development  
- **Contribution:** Open to the community  

Amatör telsiz, APRS, pico balonlar ve CubeSat gibi konulara ilgi duyan bir ekip olarak, TC3ATA adlı açık kaynaklı projemizi hayata geçirdik. Bu proje sayesinde, teori ile pratiği birleştirerek yapılandırılmış bir öğrenme ve uygulama yolculuğu sunmayı hedefliyoruz.
Ortaokul, lise ve üniversite öğrencileri başta olmak üzere, radyo amatörleri, gönüllü mühendisler, öğretmenler, STEM kulüpleri ve maker topluluklarına hitap eden bu çalışmayla, uzay temelli haberleşme teknolojilerine herkesin katkı sağlayabileceği bir ortam oluşturuyoruz.
İlk başarımızı da APRS tabanlı balon simülasyonu testimizi tamamlayarak elde ettik. Şimdi sırada daha büyük hedefler var: daha fazla deney, daha fazla paylaşım ve daha güçlü iletişim.

# TC3ATA - Uzay için Amatör Radyo Deneyleri (Türkiye)

## Genel Bakış
Bu depo, VHF, UHF, APRS, CW, dijital modlar, Meshtastic uygulamaları ve anten tasarımlarına odaklanan amatör radyo deneyimleri için adım adım bir yol haritası sunar. Amaç, temel radyo iletişiminden başlayarak gelişmiş taşınabilir ve yüksek irtifa projelerine kadar ilerlemektir.

## Yol Haritası

### 1. QSO Günlük (Logbook) Geliştirme
- Python veya web tabanlı bir logbook uygulaması geliştirme  
- QRZ ve LOTW ile entegrasyon sağlayarak QSO kayıtlarının tutulması


### 2. SSTV (Yavaş Taramalı Televizyon) Deneyleri
- HF veya ISS üzerinden SSTV görüntüleri alma  
- Robot36 ve MMSSTV ile görüntü çözümleme

![Image (9)](https://github.com/user-attachments/assets/aac700c1-64ef-4280-9fde-89747057e185) ![img_170452](https://github.com/user-attachments/assets/3af1d426-8d98-4ea0-8901-47a0acb959f3)

https://firebasestorage.googleapis.com/v0/b/ariss-sstv.appspot.com/o/img%2F170452.jpeg?alt=media

![image](https://github.com/user-attachments/assets/0acfe31f-dc6d-4331-9420-573ec8385604)


### 3. ESP ile APRS Yayını
- ESP32 ve GPS modülü kullanarak APRS üzerinden konum verisi iletme  
- APRS-IS ve RF yayını testleri

![Image (10)](https://github.com/user-attachments/assets/9aaaa431-76ee-4a32-aba7-1316610a7800)


### 4. 40M Monoband Anten ve Mors Anahtarı Geliştirme
- 40 metre bandı için bir tel anten tasarımı ve SWR ölçümleri  
- Mekanik veya 3D baskı teknikleri ile mors anahtarı yapımı

### 5. Pixie V4 ve Toroid Bobinler
- CW için düşük güçlü (QRP) Pixie V4 verici-alıcısının inşası  
- Empedans uyumu ve sinyal filtreleme için toroid bobinlerle çalışma

### 6. CW İletişim Testleri
- HF CW sinyallerini alma ve çözme  
- 5W çıkış gücüyle QSO denemeleri yapma

### 7. POTA & SOTA Aktivasyon Testleri
- Taşınabilir istasyonlar kurma ve mobil anten testleri  
- Uzun mesafe QRP iletişimi sağlama

### 8. 25W YM3XUU Dönüşümü ve Saha Testleri
- YM3XUU çağrı işareti ile 25W çıkış gücünde saha testleri yapma  
- Anten performansı ve yönlülüğünü değerlendirme

### 9. ESP ile Gelişmiş APRS ve Bluetooth/WiFi Entegrasyonu
- ESP APRS cihazını cep telefonlarına Bluetooth veya WiFi üzerinden bağlama  
- Mobil cihazlardan APRS mesajı gönderme ve izleme

### 10. Meshtastic Cihazlarıyla Mesh Ağ Kurulumu
- ESP32 tabanlı LoRa modülleri ile Meshtastic ağı kurma  
- Uzun menzilli düşük bant genişlikli iletişim testleri  
- Meshtastic üzerinden şifreli mesajlaşma ve konum paylaşımı

### 11. Meshtastic Entegrasyonu ve Alan Testleri
- Alan dışında haberleşme senaryoları test etme  
- Mobil uygulama ve Meshtastic cihazlarıyla senkronizasyon  
- Güç tüketimi ve menzil analizleri

### 12. ISS (Uluslararası Uzay İstasyonu) Alımı
- ISS üzerinden amatör radyo sinyallerini yakalama  
- Astronotlarla sesli veya veri iletişimi denemeleri

### 13. Yüksek İrtifa Balon Testi (ESP ile)
- Hafif APRS iletişim yükü tasarımı  
- Sıcaklık, basınç ve nem sensörleriyle çevresel veri iletimi  
- Dayanıklılık ve atmosferik testlerin gerçekleştirilmesi

## Depo Yapısı
- `/docs`: Teknik belgeler  
- `/firmware`: ESP32 ve Meshtastic için yazılımlar  
- `/hardware`: Antenler, balon yükleri ve el yapımı cihazlar  
- `/logs`: Alan testlerine ait kayıtlar

## Katkı Kuralları
Projeye katkıda bulunmak isteyenleri memnuniyetle karşılıyoruz:

1. Depoyu **fork**’layın  
2. Değişiklikleriniz için yeni bir **branch** oluşturun  
3. Açıklayıcı bir **pull request** gönderin  
4. Büyük değişiklikler için önce bir **issue** açarak önerilerinizi tartışmaya sunun

## Lisans
Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

## İletişim ve Topluluk
- **Website**: http://proje.space  


---

Bu proje, amatör telsizcilik, kablosuz iletişim, yüksek irtifa balonları ve Meshtastic gibi alanlara ilgi duyan meraklılar, öğrenciler ve araştırmacılar için kapsamlı bir başvuru kaynağıdır.


# TC3ATA - Amateur Radio Experiments for Space (Türkiye)

## Overview
This repository provides a step-by-step roadmap for amateur radio experiments focusing on HF, VHF, UHF, APRS, CW, digital modes, Meshtastic applications, and antenna designs. The aim is to advance from basic radio communications to sophisticated portable and high-altitude projects.

## Roadmap

### 1. QSO Logbook Development
- Creating a logbook application using Python or a web-based solution  
- Integrating with QRZ and LOTW for QSO record management


  
### 2. SSTV (Slow Scan Television) Experiments
- Receiving SSTV images via HF or ISS transmissions  
- Decoding images using Robot36 and MMSSTV

![Image (9)](https://github.com/user-attachments/assets/aac700c1-64ef-4280-9fde-89747057e185)![img_170452](https://github.com/user-attachments/assets/3af1d426-8d98-4ea0-8901-47a0acb959f3)

https://firebasestorage.googleapis.com/v0/b/ariss-sstv.appspot.com/o/img%2F170452.jpeg?alt=media

![image](https://github.com/user-attachments/assets/ec6df0b5-af44-4be1-a72e-a32c1b809288)






### 3. APRS Transmission Using ESP
- Transmitting GPS-based position data over APRS using ESP32  
- Testing APRS-IS and RF signal transmission


![Image (10)](https://github.com/user-attachments/assets/9aaaa431-76ee-4a32-aba7-1316610a7800)

### 4. 40M Monoband Antenna and Morse Paddle Development
- Designing a wire antenna for the 40-meter band and measuring SWR  
- Building a Morse paddle using mechanical or 3D printing methods

### 5. Pixie V4 and Toroidal Coils
- Constructing a low-power (QRP) Pixie V4 transceiver for CW  
- Using toroidal coils for impedance matching and signal filtering

### 6. CW Communication Tests
- Receiving and decoding HF CW signals  
- Conducting QSO attempts with 5W output power

### 7. POTA & SOTA Activation Tests
- Setting up portable radio stations and testing mobile antennas  
- Establishing long-distance QRP communication

### 8. 25W YM3XUU Conversion and Field Testing
- Conducting field operations with 25W output under the YM3XUU call sign  
- Evaluating antenna performance and directionality

### 9. Enhanced ESP APRS with Bluetooth/WiFi Integration
- Connecting the ESP APRS device to smartphones via Bluetooth or WiFi  
- Sending and viewing APRS messages from a mobile device

### 10. Mesh Network with Meshtastic Devices
- Setting up a LoRa-based Meshtastic mesh network using ESP32 modules  
- Testing long-range, low-bandwidth encrypted communication  
- Sharing GPS and messaging data across nodes

### 11. Meshtastic Integration and Field Trials
- Testing communication scenarios in off-grid conditions  
- Synchronizing mobile apps with Meshtastic devices  
- Analyzing range and power consumption

### 12. ISS (International Space Station) Reception
- Capturing amateur radio signals from the ISS  
- Attempting voice or data communication with astronauts

### 13. High-Altitude Balloon Test with ESP
- Designing a lightweight APRS payload for tracking  
- Integrating temperature, pressure, and humidity sensors  
- Conducting endurance and atmospheric flight tests

## Repository Structure
- `/docs`: Technical documentation  
- `/firmware`: ESP32 and Meshtastic firmware  
- `/hardware`: Antennas, balloon payloads, and DIY gear  
- `/logs`: Field test logs and QSO records

## Contribution Guidelines
We welcome contributions from the community:

1. **Fork** the repository  
2. Create a **new branch** for your changes  
3. Submit a **pull request** with a clear description  
4. For major changes, open an **issue** first to discuss the proposal

## License
This project is licensed under the [MIT License](LICENSE).

## Contact & Community
- **Website**: http://proje.space  


---

This project serves as a comprehensive guide for amateur radio enthusiasts, students, and researchers interested in wireless communication, portable systems, high-altitude ballooning, and Meshtastic mesh networks.


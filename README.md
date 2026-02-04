

# 🏛️ Microprocessors Course Labs (Mikroişlemciler)

Bu depo (repository), **Bilgisayar Mühendisliği** lisans programı **Mikroişlemciler** dersi kapsamında; **PIC16F887** mimarisi ve **Bare-Metal C** programlama teknikleri kullanılarak geliştirilen laboratuvar projelerini ve dönem sonu çalışmalarını içerir.

Projeler, mikroişlemci iç yapısını (Architecture), bellek yönetimini ve çevre birimlerini (Peripherals) en alt seviyede (Register-Level) kontrol etme yetkinliğini göstermektedir.

## 🎯 Proje Amacı ve Kazanımlar
Bu çalışmaların temel amacı, hazır kütüphaneler (HAL) olmadan donanımla doğrudan etkileşim kurarak aşağıdaki yetkinlikleri kazanmaktır:
* **CPU Mimarisi:** Harvard Mimarisi, Komut Çevrimi (Instruction Cycle) ve Kesme Vektör Tablosu (IVT).
* **Donanım Kontrolü:** GPIO, Timer, ADC ve PWM modüllerinin Register manipülasyonu ile sürülmesi.
* **Zamanlama Analizi:** Donanımsal zamanlayıcılar ile hassas zaman yönetimi.
* **Sinyal İşleme:** Analog sensör verilerinin dijitalleştirilmesi ve motor kontrol döngüleri.

## 📂 Proje Listesi

Bu depo, ders müfredatına paralel olarak modüler bir yapıda düzenlenmiştir:

| Klasör | Konu | İçerik ve Teknik Detay |
| :--- | :--- | :--- |
| `/01_Basic_IO` | **GPIO & Bitwise Ops** | Port yönlendirme (TRIS), Latch işlemleri ve "Kara Şimşek" (Shift) algoritmaları. |
| `/02_Display` | **Multiplexing** | Tek port üzerinden tarama (scanning) yöntemiyle 0-99 butonlu sayıcı ve 7-Segment kontrolü. |
| `/03_Sensors` | **ADC & Hysteresis** | LM35 sıcaklık sensörü ile histerezis (tolerans) kontrollü akıllı klima sistemi. |
| `/04_Interrupts` | **ISR & Timers** | Timer0 kesmesi ile **10ms hassasiyetli kronometre** ve RB0 harici kesme yönetimi. |
| `/05_Motor_Control` | **PWM & CCP** | CCP modülü (Capture/Compare/PWM) kullanılarak potansiyometre kontrollü motor sürücü. |
| `/99_Final_Project` | **Endüstriyel Kontrol** | Tüm modüllerin birleşimi: LCD arayüzlü, kesme tabanlı sistem izleme ve güvenlik paneli. |

## 🛠️ Teknik Altyapı
* **Mikrodenetleyici:** Microchip PIC16F887 (8-Bit RISC)
* **Derleyici:** MikroC PRO for PIC
* **Simülasyon:** Proteus ISIS
* **Programlama Yaklaşımı:** Bare-Metal Embedded C

## 🚀 Gelecek Adımlar
Bu depo, 8-bit mimari temellerine odaklanmaktadır. İleri seviye 32-bit ARM Cortex mimarisi ve RTOS uygulamaları, gelecekteki **Embedded Systems** deposunda yer alacaktır.

---
**[Adın Soyadın]**
Computer Engineering Student

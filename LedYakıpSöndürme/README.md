💡 Arduino Uno ile Temel LED Yakıp Söndürme (Blink)

Bu proje, Arduino dünyasına ilk adım atmak ve temel dijital çıkış mantığını kavramak amacıyla yapılmış klasik bir **Blink** uygulamasıdır.

## 🛠️ Kullanılan Malzemeler
* 1 adet Arduino Uno R3
* 1 adet LED (İstediğin renk)
* 1 adet 220 Ohm Direnç
* Jumper kablolar
* Breadboard

## 🔌 Devre Bağlantı Şeması
1. **Arduino (Pin 13)** ➔ **220 Ohm Direnç** ➔ **LED'in Uzun Bacağı (Anod)**
2. **LED'in Kısa Bacağı (Katod)** ➔ **Arduino (GND)**

## 🚀 Nasıl Çalıştırılır?
1. Donanım bağlantılarını yukarıdaki şemaya göre tamamlayın.
2. Arduino IDE'yi açın ve `codes/blink.ino` dosyasındaki kodu kartınıza yükleyin.
3. 13 numaralı pine bağlı olan LED'in 1 saniye aralıklarla yanıp söndüğünü gözlemleyin!

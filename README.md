# Nextion Ekran Kullanımı

Bu proje, Wemos D1 Mini mikrodenetleyici kartı ile 2.4 inç Nextion ekranını kullanarak internet üzerinden zaman bilgisini alıp ekrana yazdıran bir örnek uygulamadır.

## Proje Amaçları

- ESP8266 tabanlı Wemos D1 Mini kullanarak Nextion ekran ile iletişim kurmak.
- NTP (Network Time Protocol) kullanarak internetten zaman bilgisi almak.
- Alınan saat ve tarih bilgisini Nextion ekranında göstermek.

## Projenin Özellikleri

- Nextion ekranın temel özelliklerini kullanarak saat ve tarih bilgisini ekrana yazdırma.
- WiFi bağlantısı üzerinden NTP kullanarak internetten zaman bilgisi alma.
- EasyNextionLibrary kullanılarak kolayca Nextion ekran ile etkileşim sağlama.

## Kullanılan Kütüphaneler

- [EasyNextionLibrary](https://github.com/itead/EasyNextionLibrary): Nextion ekran ile etkileşim için kullanılan kütüphane.
- [NTPClient](https://github.com/arduino-libraries/NTPClient): NTP protokolü kullanarak internetten saat ve tarih bilgisi almak için kullanılan kütüphane.
- [ESP8266WiFi](https://arduino-esp8266.readthedocs.io/en/latest/esp8266wifi/readme.html): ESP8266 tabanlı mikrodenetleyici kartının Wi-Fi bağlantısı için kullanılan kütüphane.

## Bağlantı Şeması

Projenin bağlantı şemasını aşağıda bulabilirsiniz:

- Wemos D1 Mini RX pin --> Nextion ekran TX pin
- Wemos D1 Mini TX pin --> Nextion ekran RX pin
- Wemos D1 Mini 5V pin --> Nextion ekran 5V pin
- Wemos D1 Mini GND pin --> Nextion ekran GND pin

## Nextion Ekran Uygulaması

Projenin Nextion Editör Uygulamasının t0 ve t1 Textinin Ayarları ve Arka Plan Resminin Yüklenmesi.

![Ekran Görüntüsü (1)](https://github.com/recepuysal/Nextion-Ekran-Kullanimi/assets/148240525/2b46252e-78c8-4aa5-8679-3af5df19f762)



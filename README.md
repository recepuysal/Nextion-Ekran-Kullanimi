# Nextion Ekran Kullanımı

Bu proje, 2.4 inç Nextion ekranını Wemos D1 Mini mikrodenetleyici kartı ile kullanarak internetten saat ve tarih bilgisini alıp ekranda gösterme amacını taşımaktadır.

## Proje Açıklaması

Bu projede ESP8266 tabanlı Wemos D1 Mini mikrodenetleyici kartı kullanılarak, Nextion ekranı ile iletişim kurulmuş ve internetten NTP (Network Time Protocol) üzerinden zaman bilgisi alınarak ekrana yazdırılmıştır.

## Kullanılan Kütüphaneler

- [EasyNextionLibrary](https://github.com/itead/EasyNextionLibrary): Nextion ekran ile iletişim kurmak için kullanılan kütüphane.
- [NTPClient](https://github.com/arduino-libraries/NTPClient): NTP protokolü kullanılarak internetten saat ve tarih bilgisi almak için kullanılan kütüphane.
- [ESP8266WiFi](https://arduino-esp8266.readthedocs.io/en/latest/esp8266wifi/readme.html): ESP8266 tabanlı mikrodenetleyici kartının Wi-Fi bağlantısı için kullanılan kütüphane.

## Bağlantılar

- [Nextion Resmi Websitesi](https://nextion.tech/)
- [Wemos D1 Mini Resmi Websitesi](https://www.wemos.cc/en/latest/d1/index.html)

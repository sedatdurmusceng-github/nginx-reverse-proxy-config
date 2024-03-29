NGINX ile Güvenli Veri İletişimi ve Performans: Reverse Proxy, Load Balancer ve SSL Kullanımı
===============

Yayınlanan mikro servislerin Reverse Proxy, Load Balancer yönlendirme ve SSL kullanım ayarlarını ve alt yapısını içerir.

## Dizin Yapısı

**certs:** SSL sertifikalarını barındırır.

**config:** Yönlendirme ayarlarını barındırır. İçerisinde bulunan nginx.conf dosyasında bu ayarlar mevcuttur.

**logs:** log dosyalarını barındırır.

**docker-compose.yml:** Load Balancer olarak NGINX kullanılmaktadır. NGINX yapısını ayaklandırmak için kullanılan dosyadır.

## Kurulum

- docker-compose.yml dosyasının bulunduğu dizinde Terminal ekranı açılır.
- "docker-compose up -d" komutu çalıştırılarak gerekli yazılım ve servisler Docker üzerinde ayaklandırılır.
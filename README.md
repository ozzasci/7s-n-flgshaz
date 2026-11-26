# Sosyal7 Arena (Proje Kimliği: sosyal7-arena)

Bu paket, **sosyal7-arena** Firebase projesine bağlı, bağımsız bir eğitim ve düello uygulamasıdır.

## İçerik
- `index.html`: 430 benzersiz soru (250 7. Sınıf Sosyal Bilgiler + 100 LGS 5 Deneme + 40 Kolej Zor + 40 Olimpiyat), düello odası ve profil/istatistik ekranları.
- `manifest.json`, `icon-192.png`, `icon-512.png`: Ana ekrana uygulama olarak kurulum dosyaları.
- `soru_havuzu_yedek.json`: Tüm 430 sorunun JSON yedeği.

## Firebase Realtime Database Kuralları
Canlı düello odalarının (`sosyal7_proje_duello`) ve kullanıcı profillerinin (`sosyal7_proje_kullanicilar`) sorunsuz çalışması için Firebase Console'da **Realtime Database > Rules** sekmesinde okuma ve yazma izinlerinin açık olduğundan emin olun.

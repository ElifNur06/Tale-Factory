own
# Masal Fabrikası (Tale Factory) 📖✨

Masal Fabrikası, çocukların kişisel tercihlerine (isim, sevdiği oyuncak, korkular vb.) göre yapay zeka ile özelleştirilmiş masallar üreten, interaktif öğrenme araçları sunan ve sesli hikaye anlatımı sağlayan eğitim odaklı bir mobil uygulamadır.

## 🚀 Temel Özellikler

- **AI Destekli Masal Üretimi:** Google Gemini API ile çocuğun profil verilerine göre dinamik ve kişiselleştirilmiş hikayeler.
- **İnteraktif Öğrenme:** - **Sözlük:** Masal metnindeki kelimelere tıklandığında anlık anlam görüntüleme.
    - **Quiz Modülü:** Üretilen hikayeye göre otomatik oluşturulan 3 soruluk eğitici testler.
- **Sesli Anlatım & Kayıt:** - **TTS (Text-to-Speech):** Hikayenin yapay zeka tarafından seslendirilmesi.
    - **Ses Kaydı:** Kullanıcının kendi sesini kaydedip hikayeyi kendi sesinden dinleyebilmesi.
- **Yabancı Dil Desteği:** "İngilizce Öğrenme Modu" ile basit İngilizce seviyesinde masal üretimi ve dil pratiği.
- **Uyku Modu:** Göz yormayan, düşük ışıklı ekran modu ile gece hikaye dinleme deneyimi.
- **Dallanan Hikaye Yapısı:** "Kendi Maceranı Seç" modu ile çocukların seçim yapabildiği interaktif kurgu.
- **Görsel Üretim:** Pollinations API ile her masala özel kapak resmi üretimi.
- **PDF Dışa Aktarım:** Üretilen masalların görsel ve metin içeriğiyle PDF formatında paylaşılabilmesi.

## 🛠 Teknik Altyapı (Tech Stack)

| Kategori | Teknoloji / Kütüphane |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **Veritabanı** | SQFlite (SQLite) |
| **Yapay Zeka** | Google Gemini API (gemini-2.5-flash) |
| **Görsel Üretim** | Pollinations API |
| **Ses/Konuşma** | `flutter_tts`, `audioplayers`, `record` |
| **PDF/İndirme** | `pdf`, `printing` |
| **Veri Kalıcılığı** | `shared_preferences` |


## Görseller
<img width="337" height="600" alt="image" src="https://github.com/user-attachments/assets/2070ea1e-0d16-47ed-b589-9eafd7a32a78" />
<img width="336" height="597" alt="image" src="https://github.com/user-attachments/assets/a196e6b5-3b30-4de8-ac85-b4b0bbf4b14d" />
<img width="337" height="598" alt="image" src="https://github.com/user-attachments/assets/d683d167-e29c-4cc8-a91a-c3663a867a00" />
<img width="338" height="599" alt="image" src="https://github.com/user-attachments/assets/072794f6-2a11-4884-a710-4e778e855a79" />
<img width="339" height="595" alt="image" src="https://github.com/user-attachments/assets/fc8b0fcd-8309-4377-857d-98f7b9c1a2fc" />
<img width="334" height="597" alt="image" src="https://github.com/user-attachments/assets/e8cd66ee-f430-4d99-9e94-4ccf955d7620" />
<img width="337" height="597" alt="image" src="https://github.com/user-attachments/assets/2154724e-717f-4d60-bcb7-6e670fcc293d" />
<img width="338" height="600" alt="image" src="https://github.com/user-attachments/assets/6df26e96-c1d7-48d6-befa-48a1dc92eff0" />
<img width="335" height="595" alt="image" src="https://github.com/user-attachments/assets/60689520-3ec7-4eed-8836-7933d8389605" />
<img width="335" height="598" alt="image" src="https://github.com/user-attachments/assets/c33a4b9d-614b-4963-8480-c6db8be3f957" />
<img width="337" height="600" alt="image" src="https://github.com/user-attachments/assets/7a799abc-3dbb-4380-8688-f57cf0df952e" />


## 🏗 Sistem Mimarisi
Veri Katmanı: SQFlite (masallar_final_v8.db) üzerinden masal içeriklerini, quiz ve sözlük verilerini kalıcı olarak saklar.

Logic Katmanı: Generative Model üzerinden istemci-sunucu iletişimi ve '|||' ayraçlı metin parse etme mekanizması ile hikaye kurgusu yönetilir.

Güvenlik: Premium üyelik doğrulama kontrolleri ve API key yönetimi merkezi bir yapıda tutulur.

Masal Fabrikası - Hayal Gücünü Yapay Zeka ile Tasarla.

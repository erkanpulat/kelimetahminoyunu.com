# 🔗 [kelimetahminoyunu.com](https://kelimetahminoyunu.com/) - KTO ![Status: Alpha](https://img.shields.io/badge/status-alpha-orange)

**🚧 İlk Sürüm – Yol haritasındaki özellikler geliştirilmeye devam edecektir.**

---

## 🎯 Proje Amacı ve Hikayesi

Kelime Tahmin Oyunu, **verilen harflerle anlamlı kelimeler türeterek puan ve altın kazandığınız, skor tablosunda yükselmeye odaklı rekabetçi bir Türkçe kelime bulmaca oyunudur**. Oyunun kullanıcı deneyimi ve performansı, masaüstü ve mobil tarayıcılar için optimize edilmiştir.

📝 Bu proje, hayatımın zorlu bir döneminde doğdu. Geçirdiğim ameliyat sonrası iyileşme sürecinde, zamanımı değerlendirmek için kelime tahmin oyunlarını sıkça oynamaya başladım. Bir süre sonra bu oyunlarla yalnızca eğlenmekle kalmadım; oyunların mekaniklerini gözlemleyerek şunu düşündüm:

> *“Bunu daha rekabetçi, zorlu ve daha keyifli nasıl yapabilirim?”*

İlk denemelerimde, çeşitli canlı yayın platformlarında **izleyicilerin yazdığı kelimeleri yakalayıp onları birbirleriyle yarıştıran** ve birçok özelliği barındıran (ilerleyen süreçte bu projeye de eklenecek) bir uygulama geliştirdim. Kullanıcılar tarafından oldukça sevildi ve oynandı. Bu deneyim, projeyi **bağımsız bir web oyunu** hâline getirme fikrinin temelini attı. Sonrasında KTO’nun ilk sürümünü yayına alarak oyuncularla buluşturmuş oldum.

## 🚩 Proje Geliştirme Özet Süreci

Proje, uçtan uca tüm aşamalarında titizlikle geliştirilmiştir:

* Kullanıcı arayüzünün tasarımı ve Angular 20 kullanılarak yüksek performanslı SSR (Server Side Rendering) altyapı kurulumu
* Sunucu tarafının NestJS ile güçlü ve esnek bir mimari üzerine inşası
* Gerçek zamanlı veri akışı, oyun sekronizasyonu ve hile girişimlerinin önlenmesi için Socket.IO altyapısının kurulumu
* MongoDB ile depolanması, Mongoose ODM ile yönetimi
* Kimlik doğrulama sistemlerinin JWT ve Google OAuth 2.0 ile güvenli biçimde entegrasyonu
* Google Cloud platformunda VM instance üzerinde Linux (Ubuntu), Nginx ve PM2 ile sunucu kurulumu SSL sertifikası entegrasyonu ile güvenli (HTTPS) bağlantı sağlanması
* Digital Ocean Droplet *(önceki sürümler: GCP VM Instance)* üzerinde Linux (Ubuntu), Nginx ve PM2 ile sunucu kurulumu, SSL sertifikası (Let’s Encrypt) entegrasyonu ile güvenli (HTTPS) bağlantı sağlanması

## ⚙️ Kullanılan Ana Teknolojiler

![Angular](https://img.shields.io/badge/Frontend-Angular%2020-DD0031?logo=angular)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap%205-7952B3?logo=bootstrap)
![Socket.IO](https://img.shields.io/badge/Realtime-Socket.IO%20Client%204-black?logo=socketdotio)
![NestJS](https://img.shields.io/badge/Backend-NestJS%2011-E0234E?logo=nestjs)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb)
![Mongoose](https://img.shields.io/badge/ODM-Mongoose-880000)
![JWT](https://img.shields.io/badge/Auth-JWT-000000?logo=jsonwebtokens)
![OAuth](https://img.shields.io/badge/Auth-Google%20OAuth%202.0-4285F4?logo=google)
![DigitalOcean](https://img.shields.io/badge/Hosting-Digital%20Ocean-0080FF?logo=digitalocean)
![Nginx](https://img.shields.io/badge/Server-Nginx-009639?logo=nginx)
![PM2](https://img.shields.io/badge/Process%20Manager-PM2-2C3E50)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%2025.04-E95420?logo=ubuntu)
![SSL](https://img.shields.io/badge/Security-Let’s%20Encrypt-003A70?logo=letsencrypt)

* **Frontend:** Angular 20 (SSR), Bootstrap 5, Socket.IO Client 4
* **Backend:** NestJS 11, MongoDB - Mongoose, Passport (JWT & Google OAuth 2.0), Socket.IO 4 Gateway
* **Sunucu & Altyapı:** Digital Ocean Droplet (önceki: GCP VM Instance), Linux (Ubuntu), Nginx, PM2, SSL (Let’s Encrypt)

## 🌐 Canlı Demo Bağlantıları

| Sayfa         | Bağlantı                                                                                    |
| ------------- | ------------------------------------------------------------------------------------------- |
| Ana Sayfa     | [https://kelimetahminoyunu.com](https://kelimetahminoyunu.com/)                             |
| Nasıl Oynanır?| [https://kelimetahminoyunu.com/nasil-oynanir](https://kelimetahminoyunu.com/nasil-oynanir/) |
| Blog          | [https://kelimetahminoyunu.com/blog](https://kelimetahminoyunu.com/blog/)                   |
| İletişim      | [https://kelimetahminoyunu.com/iletisim](https://kelimetahminoyunu.com/iletisim/)           |

## 📸 Ekran Görüntüleri

<p align="center">
  <img src="https://github.com/user-attachments/assets/2aaf5d47-e464-4517-864a-f4ce2227bcee" alt="Ana Sayfa" width="800"/>
  <br/><em>Ana Sayfa</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/99797542-2479-41bb-8059-f9473f276990" alt="Mobil Oyun Ekranı" width="350"/>
  <img src="https://github.com/user-attachments/assets/ea778b29-9a4c-4168-a52b-3eb6666b93cb" alt="Mobil Oyun Ekranı (Klavye Açık)" width="350"/>
  <br/><em>Mobil oyun deneyimi ve klavye etkileşimi</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1cbcbc27-8a50-4554-b5cf-01d37568d5db" alt="Nasıl Oynanır Sayfası" width="800"/>
  <br/><em>Statik Sayfalar - "Nasıl Oynanır?" Sayfası Kesit</em>
</p>

---

> Bu belge, **v1.0.0‑α** sürüm notu ile yayımlanmıştır. Yeni özelliklerle birlikte güncellenecektir.

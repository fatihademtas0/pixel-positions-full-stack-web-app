# 🏦  Pixel Positions - İş İlanları Projesi

Bu proje, Laravel 11 kullanılarak geliştirilmiş bir iş ilanları platformudur. Kullanıcılar iş ilanlarını görüntüleyebilir, arayabilir ve kendi ilanlarını oluşturabilirler.

## 🚀 Özellikler

- İş ilanlarını görüntüleme
- İş ilanı oluşturma
- İş ilanlarında arama yapma
- Etiketlere göre filtreleme
- Kullanıcı kaydı ve girişi
- Oturum yönetimi

## ✂️ Ekran Görüntüleri

## Misafir Ana Ekranı
![home](https://github.com/user-attachments/assets/fe456643-38fd-4739-bef2-54dc97aee406)


## Oturum Açmış Kullanıcı Ana Ekranı
![auth-home](https://github.com/user-attachments/assets/68457aa3-3745-4e6a-aece-d81c9571be78)


## Kaydolma Ekranı
![register](https://github.com/user-attachments/assets/4c8669a6-bbb6-44be-8d84-dbbd8c1c35bb)


## Giriş Yapma Ekranı
![login](https://github.com/user-attachments/assets/134eebf7-bc4a-476f-8c11-3ff24a70f8b5)


## İş İlanı oluşturma Ekranı
![postingJob](https://github.com/user-attachments/assets/0f5ced77-7e52-4b8c-be2d-30ae13db3fba)


## Etiket Oluşturma Ekranı
![tag](https://github.com/user-attachments/assets/28e4eebd-375a-42f8-a801-654bab2aaec3)


## Etiketler ve Son Eklenen İlanlar Ekranı
![tags-and-recent-jobs](https://github.com/user-attachments/assets/17e6de4f-841b-40f1-b1df-50a9acaa401a)




## 💻 Teknolojiler

- PHP 8.2
- Laravel 11.38.2
- SQLite Veritabanı
- TailwindCSS 3.4.17
- Node.js & NPM
- Vite

## 🏗️ Proje Yapısı

### Backend Yapısı
- **Controllers/**
  - `JobController.php` - İş ilanları yönetimi
  - `RegisteredUserController.php` - Kullanıcı kaydı işlemleri
  - `SearchController.php` - Arama fonksiyonları
  - `SessionController.php` - Oturum yönetimi
  - `TagController.php` - Etiket işlemleri

### Paket Yapısı
#### PHP Paketleri
- `laravel/framework:v11.38.2` - Laravel çerçevesi
- `mockery/mockery:1.6.12` - Test dublörü kütüphanesi
- `guzzlehttp/guzzle:7.9.2` - HTTP istemcisi
- `fakerphp/faker:v1.24.1` - Test verisi oluşturma
- `monolog/monolog:3.8.1` - Loglama sistemi
- `brianium/paratest:v7.7.0` - Paralel test çalıştırma
- `symfony/mailer:v7.2.0` - E-posta işlemleri

#### JavaScript Paketleri
- `axios:1.7.4` - HTTP istemcisi
- `postcss:8.5.1` - CSS işleme
- `tailwindcss:3.4.17` - CSS framework
- `vite` - Frontend araç zinciri
- `laravel-vite-plugin` - Laravel Vite entegrasyonu

### Veritabanı Yapısı
- SQLite veritabanı kullanılmaktadır
- Queue işlemleri için database sürücüsü kullanılmaktadır


## 📚 API Endpoints

| Method | URL | Açıklama |
|--------|-----|----------|
| GET | / | Ana sayfa - İş ilanları listesi |
| GET | /jobs/create | İş ilanı oluşturma formu |
| POST | /jobs | Yeni iş ilanı oluşturma |
| GET | /search | İş ilanlarında arama |
| GET | /tags/{tag} | Etikete göre ilanları filtreleme |
| GET | /register | Kayıt formu |
| POST | /register | Yeni kullanıcı kaydı |
| GET | /login | Giriş formu |
| POST | /login | Kullanıcı girişi |
| DELETE | /logout | Çıkış yapma |


## 🛠️ Kurulum

Projenin çalışması için aşağıdaki adımları izle:

### 1. Depoyu Klonlayın
Projeyi bilgisayarınıza klonlamak için aşağıdaki komutu kullanabilirsiniz:

```bash
git clone https://github.com/fatihademtas0/pixel-positions-full-stack-web-app.git
cd pixel-positions-full-stack-web-app
```

### 2. Composer bağımlılıklarını yükleyin:
Projenin bağımlılıklarını yüklemek için aşağıdaki komutu çalıştırın:

```bash
bash composer install 
```

### 3. NPM bağımlılıklarını yükleyin:

```bash
bash npm install
```

### 4. Vite ile frontend varlıklarını derleyin:

```bash
bash npm run dev
```

### 5. Uygulamayı Çalıştırın
Projeyi yerel sunucuda çalıştırmak için aşağıdaki komutu kullanın:

```bash
bash php artisan serve
```

### 6. Uygulamayı Görüntüle
Bu komut, uygulamayı http://localhost:3000 adresinde başlatacaktır.

# Laravel Forum Sitesi

Bu proje, Laravel kullanılarak geliştirilmiş bir forum sitesidir.

## Özellikler

- Kullanıcı kayıt/giriş sistemi
- Konu açma ve yorum yapma
- Konulara upvote veya downvote verme
- Admin paneli ile kullanıcı, konu, yorum yönetimi

## Kurulum

1. Reposu klonla:
```bash
git clone https://github.com/ahmetfarukyasar/webforum.git
```
2. Gerekli paketleri yükle:
```
composer install
npm install
npm run dev
```
3. .env dosyasını oluştur ve ayarları yap:
```
cp .env.example .env
php artisan key:generate
```

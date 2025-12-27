# Askıda Yemek Sistemi (Suspended Meal System)

Bu proje, ihtiyaç sahipleri ile bağışçıları ve restoranları buluşturan bir "Askıda Yemek" platformudur.

## Özellikler

*   **Restoran Paneli**: Menü yönetimi, askıya yemek ekleme, yemek durumlarını takip etme.
*   **Yönetici Paneli (Admin)**: Kullanıcı ve restoranları yönetme, istatistikleri görüntüleme.
*   **Bağışçı ve İhtiyaç Sahibi Arayüzleri**: Yemek bağışlama ve askıdaki yemekleri görme.
*   **Harita/Isı Haritası**: Yardımların yoğunlaştığı bölgeleri görselleştirme.

## Kurulum (Lokal)

Bu projeyi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

### 1. Gereksinimler
*   Node.js (v14 veya üzeri)
*   NPM

### 2. Kurulum

**Sunucu (Server) Kurulumu:**
```bash
cd server
npm install
cp .env.example .env
npm start
```

**İstemci (Client) Kurulumu:**
```bash
cd client
npm install
npm run dev
```

## Teknoloji Yığını

*   **Frontend**: React, Vite
*   **Backend**: Node.js, Express
*   **Veritabanı**: SQLite
*   **Stil**: CSS (Vanilla), Google Fonts (Outfit)

## Klasör Yapısı

*   `/server`: Backend kodları, API endpointleri ve veritabanı.
*   `/client`: React frontend uygulaması.

# 💳 SpendControl Dashboard (Harcama Takip Paneli)

Bu proje; kullanıcıların günlük gelir ve giden dengelerini kategorize ederek takip etmelerini, harcama farkındalık skorlarını analiz etmelerini ve bütçe durumlarını izlemelerini sağlayan, harici hiçbir kütüphane kullanılmadan **Vanilla JavaScript** ile geliştirilmiş uçtan uca bir tek sayfa uygulamasıdır (SPA).

---

## 🛠️ Öne Çıkan Teknik Özellikler
- **State Management & Kalıcılık:** Veriler tarayıcı hafızasında (**Local Storage**) kullanıcı bazlı olarak saklanır. Sayfa yenilense veya tarayıcı kapatılsa bile durum (state) korunur.
- **Custom Canvas Graphics:** Grafik gösterimi için Chart.js gibi harici kütüphaneler yerine, ham **HTML5 Canvas API** (`2D Context`) kullanılarak matematiksel oranlamalarla sıfırdan dinamik sütun grafik motoru yazılmıştır.
- **Dinamik Filtreleme Hattı:** Girilen harcamalar; kategori filtreleri, arama sorguları ve bütçe durumlarına göre asenkron DOM manipülasyonu ile anlık olarak filtrelenir.
- **Akıllı Bütçe Algoritması:** Toplam harcama miktarı belirlenen bütçe limitini aştığında sistem otomatik olarak CSS tabanlı dinamik uyarı sınıflarını tetikler.

---

## 🏗️ Proje Yapısı
```text
SpendControl-Dashboard/
│
├── index.html          # HTML yapısı, inline CSS stilleri ve Vanilla JS lojikleri
└── README.md           # Proje dökümantasyonu

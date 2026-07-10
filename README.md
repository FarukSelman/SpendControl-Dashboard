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
```
🚀 Kullanılan Teknolojiler
HTML5 (Canvas API & Yapısal Düzen)

CSS3 (Flexbox, Grid Sistemleri ve Dinamik Uyarı Arayüzleri)

Vanilla JavaScript (ES6+) (Local Storage API, Data Filtering, Asynchronous DOM Rendering, Canvas 2D Painting)

🔧 Kurulum ve Çalıştırma
Projenin çalışması için herhangi bir paket yöneticisi (npm, yarn) veya harici bir bağımlılık kurulumuna gerek yoktur.

Projeyi bilgisayarınıza klonlayın veya index.html dosyasını indirin:
```bash
git clone [https://github.com/FarukSelman/SpendControl-Dashboard.git](https://github.com/FarukSelman/SpendControl-Dashboard.git)
```
index.html dosyasını herhangi bir modern web tarayıcısında (Chrome, Edge, Safari, Firefox) çift tıklayarak veya bir yerel sunucu (Live Server vb.) üzerinden doğrudan çalıştırabilirsiniz.

💡 Bu proje; tarayıcı depolama birimleri, gelişmiş DOM manipülasyonu ve grafik kütüphanelerinin arkasında yatan matematiksel Canvas çizim mantıklarını kavramak amacıyla geliştirilmiş bağımsız bir ön yüz (Frontend) çalışmasıdır.
